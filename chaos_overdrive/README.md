# CHAOS OVERDRIVE

Private Sandbox Control & Cheat Suite, for your own single-player game.

## Turning it on and off

It's off by default, and with it off the game is unchanged.

- **On:** Main menu → Mods → tick **CHAOS OVERDRIVE**, then start a game.
- **Open the menu:** **F6** during play, or the button in the Mod Menu (M). F6, Esc or ✕ closes it.
- **Off:** untick it in the Mods screen. Every setting is undone, and what it created is removed. To keep things it created, turn its effects off from the menu instead.

## Keys

| Action | Default key |
| --- | --- |
| Open or close the menu | F6 |
| Select what's under the crosshair | F7 |
| Stop all effects | F8 |

Change them under *Profiles & Settings*. The game's own keys and F5, F11 and F12 can't be taken.

## How it works

The mod's logic is all ChaosScript, in this folder. Settings are kept in the game's mod storage, and it makes no network connections.

Everything that changes the game goes through the `sandbox` API, which records how to undo each change. That's why turning the mod off restores things even though a stopped script can't run: the game does it. Effects also end with each session, and the mod applies your profile again when the next one starts.

## What isn't there

These show as UNAVAILABLE in the menu, with the reason:

- Rain, snow and wind: the engine has no such system. Weather here means sky, light and fog.
- Survival lives and challenge budgets: no API reaches them.
- Inventory and ammunition pickups: the game has neither. Weapons are hotbar slots with energy bars.
- System commands and arbitrary files: deliberately left out, as with every mod.

## Limits

- Spawning: up to 100 per request, confirmation above 10, at least 0.05 s apart, one job at a time. It stops if the frame rate falls below 8, and the game's own entity limits and its 60-per-second limit for mods still apply.
- Weapon tuning applies to all weapons together, not to one.
- Saved games store the session's real gravity, damage and aggression, not the overrides. Objects you changed, such as a new size or material, are saved as they are at that moment.
- With two mods using the `sandbox` API on the same value, whichever set it first owns restoring it.
