# CHAOS OVERDRIVE functions

Every row of the menu in version 1.0.0, by category and section. Search in the menu finds them by name.

## Player (8)

### Protection

| Function | Type | Notes |
| --- | --- | --- |
| God Mode | Switch | No damage, full health, and blasts don't throw you. |
| Invulnerable | Switch | Turns off the session's player damage rule. Knockback still happens. |
| NPCs Ignore Me | Switch | Sets NPC aggression to passive unless you hurt them first. |
| Full Health | Button |  |
| Respawn | Button |  |

### Resources

| Function | Type | Notes |
| --- | --- | --- |
| Infinite Energy | Switch | Every weapon and tool stays fully charged. |
| Refill Energy Now | Button |  |
| Survival Lives & Challenge Budgets | **Unavailable** | These belong to their game modes, and no API can reach them. Energy is the only general resource. |

### Status

| Function | Type | Notes |
| --- | --- | --- |
| Reset Player & Movement | Button |  |

## Movement (9)

### On foot

| Function | Type | Notes |
| --- | --- | --- |
| Movement Speed | Slider |  |
| Jump Height | Slider |  |
| Player Gravity | Slider | What only you feel. 0 floats. |
| Air Control | Slider |  |
| Launch Upward | Button |  |

### Flight

| Function | Type | Notes |
| --- | --- | --- |
| Free Flight | Switch | Fly with solid collisions, in any game mode. Space up, Ctrl down. While flying, the game itself makes you untargetable. |
| No Clip | Switch | Fly through walls and objects. |
| Flight Speed | Slider |  |
| Reset Movement | Button |  |

## Physics (21)

### World

| Function | Type | Notes |
| --- | --- | --- |
| Gravity Multiplier | Slider | Negative pulls upward. |
| Gravity Off | Switch |  |
| Pause Physics Objects | Switch | Holds every object and NPC still, keeping its motion. You can still move. |

### Selected object

| Function | Type | Notes |
| --- | --- | --- |
| Select Under Crosshair | Button |  |
| Or Pick Something Nearby | List |  |
| Frozen in Place | Switch |  |
| Mass | Slider |  |
| Its Gravity | Slider |  |
| Air Resistance | Slider |  |
| Size | Slider |  |
| Material | List | Friction, bounce, weight and impact sound. |
| Restore Original Properties | Button |  |
| Remove It | Button |  |

### Moving it

| Function | Type | Notes |
| --- | --- | --- |
| Push Strength | Slider | Change in speed for any mass. |
| Push Direction | List |  |
| Push | Button |  |
| Stop Its Motion | Button |  |
| Lift 2 m | Button |  |
| Bring to Me | Button |  |
| Carry It | Switch | Holds it three metres ahead of you until turned off. |
| Restore All Changed Objects | Button |  |

## NPC Control (19)

### Create

| Function | Type | Notes |
| --- | --- | --- |
| NPC Type | List |  |
| Create at Crosshair | Button |  |
| Remove NPCs This Mod Created | Button |  |

### Selected NPC

| Function | Type | Notes |
| --- | --- | --- |
| NPC | List |  |
| Select Under Crosshair | Button |  |
| AI Running | Switch |  |
| Frozen in Place | Switch |  |
| Invulnerable | Switch |  |
| Stance | List | An NPC with attack "none" can't fight whatever its stance. |
| Speed | Slider |  |
| Detection Radius | Slider | Scales both sight and hearing. |

### Orders

| Function | Type | Notes |
| --- | --- | --- |
| Restore Health | Button |  |
| Follow Me | Button |  |
| Patrol Radius | Slider |  |
| Patrol Around Here | Button |  |
| Clear Orders | Button |  |
| Remove It | Button |  |

### All NPCs

| Function | Type | Notes |
| --- | --- | --- |
| Action | List |  |
| Apply to All NPCs | Button |  |

## Weapons & Items (12)

### Weapons

| Function | Type | Notes |
| --- | --- | --- |
| Give Weapon | Section |  |
| Inventory & Ammo Pickups | **Unavailable** | The game has no inventory or ammunition. Every weapon is a hotbar slot with an energy bar, so giving one means equipping it, and refilling means refilling energy. |

### Tools

| Function | Type | Notes |
| --- | --- | --- |
| Give Tool | Section |  |

### Ammo

| Function | Type | Notes |
| --- | --- | --- |
| Infinite Energy (Ammo) | Switch |  |
| Refill All Energy | Button |  |
| Unlock All Tools | Switch | For modes that limit the hotbar. |

### Tuning (all weapons)

| Function | Type | Notes |
| --- | --- | --- |
| Damage | Slider | Damage you deal, single player only. |
| Hit Force | Slider |  |
| Fire Rate | Slider | Faster cooldown and recharge. |

### Items

| Function | Type | Notes |
| --- | --- | --- |
| Item | List |  |
| Create in Front of Me | Button |  |
| Remove Under Crosshair | Button |  |
| Remove Items This Mod Created | Button |  |

## Vehicles (13)

### Create

| Function | Type | Notes |
| --- | --- | --- |
| Vehicle Type | List |  |
| Create at Crosshair | Button |  |
| Remove Vehicles This Mod Created | Button |  |

### Selected vehicle

| Function | Type | Notes |
| --- | --- | --- |
| Vehicle | List |  |
| Teleport to It | Button |  |
| Get In | Button |  |
| Repair & Right It | Button |  |
| Remove It | Button |  |
| Acceleration | Slider |  |
| Top Speed | Slider |  |
| Grip | Slider |  |
| Its Gravity | Slider |  |
| Mass | Slider |  |

## World Control (15)

### Objects

| Function | Type | Notes |
| --- | --- | --- |
| Object | List |  |
| Create at Crosshair | Button |  |
| Select Under Crosshair | Button |  |
| Remove the Selected Object | Button |  |
| Remove Everything This Mod Created | Button |  |

### Freezing

| Function | Type | Notes |
| --- | --- | --- |
| Freeze Radius | Slider |  |
| Freeze Objects Around Me | Button |  |
| Pause All Physics Objects | Switch |  |

### Lighting

| Function | Type | Notes |
| --- | --- | --- |
| Sunlight | Slider |  |
| Ambient Light | Slider |  |
| Fog | Slider |  |

### Rules

| Function | Type | Notes |
| --- | --- | --- |
| NPC Aggression | List |  |

### Saved world settings

| Function | Type | Notes |
| --- | --- | --- |
| Save World Settings | Button |  |
| Restore World Settings | Button |  |
| Back to the Map's Own | Button |  |

## Spawning (13)

### Choose

| Function | Type | Notes |
| --- | --- | --- |
| Category | List |  |
| Entity List | Section |  |

### Where and how many

| Function | Type | Notes |
| --- | --- | --- |
| Position | List |  |
| X | Slider |  |
| Y | Slider |  |
| Z | Slider |  |
| Count | Slider | Limit 100. Above 10 it asks first. |
| Interval | Slider | Time between each one. |
| Size | Slider |  |
| Fixed in Place | Switch |  |

### Do it

| Function | Type | Notes |
| --- | --- | --- |
| Spawn | Button |  |
| Cancel Spawning | Button |  |
| Remove Everything This Mod Created | Button |  |

## Visuals (10)

### On the HUD

| Function | Type | Notes |
| --- | --- | --- |
| Coordinates | Switch |  |
| FPS & Frame Time | Switch |  |
| Physics Debug Info | Switch | World totals and the selected object. |
| NPC Info | Switch | The selected NPC's state and numbers. |
| Active Effects | Switch | How many menu settings are changed. |

### In the world

| Function | Type | Notes |
| --- | --- | --- |
| Physics Colliders | Switch | Every collision shape, as lines. Expensive on big maps. |
| NPC Detection Radii | Switch | Blue is sight, amber is hearing, red is attack range. |
| NPC Movement Direction | Switch | A line along each NPC's velocity. |
| NPC State & Paths | Switch | The same view as F4: state labels and routes. |
| Highlight Selection | Switch | A yellow box around selected things. |

## Time & Weather (6)

### Simulation speed

| Function | Type | Notes |
| --- | --- | --- |
| Time Scale | Slider | Slows or speeds everything, you included. |
| Pause Physics Objects | Switch |  |

### Time of day

| Function | Type | Notes |
| --- | --- | --- |
| Control Time of Day | Switch | Maps have fixed light. This moves the sun and blends the sky. |
| Hour | Slider | Used while Control Time of Day is on. Underground and indoor areas change less. |

### Sky & weather

| Function | Type | Notes |
| --- | --- | --- |
| Sky | List |  |
| Weather | List | The game's weather is its sky and fog. |
| Rain, Snow & Wind | **Unavailable** | The engine has no precipitation or wind system. Only the sky, the light and the fog can change. |

## Teleportation (10)

### Instant

| Function | Type | Notes |
| --- | --- | --- |
| To the Crosshair | Button |  |
| 10 m Up | Button |  |
| To the Selected Object | Button |  |
| To the Map's Spawn | Button |  |

### Coordinates

| Function | Type | Notes |
| --- | --- | --- |
| X | Slider |  |
| Y | Slider |  |
| Z | Slider |  |
| Use My Position | Button |  |
| Teleport There | Button |  |

### Saved points

| Function | Type | Notes |
| --- | --- | --- |
| Saved Points | Section |  |

## Fun & Chaos (18)

### Emergency

| Function | Type | Notes |
| --- | --- | --- |
| STOP ALL EFFECTS | Button | Same as the Stop key. |

### Effect strength

| Function | Type | Notes |
| --- | --- | --- |
| Explosion Force | Slider | All explosions and shockwaves. |
| Time Scale | Slider |  |

### Experiments

| Function | Type | Notes |
| --- | --- | --- |
| Area Radius | Slider |  |
| Force | Slider |  |
| Duration | Slider |  |
| Impulse on Everything Nearby | Button |  |
| Impulse on This Mod's Objects | Button |  |
| Explosion at Crosshair | Button |  |
| Shockwave Around Me | Button |  |

### Random experiments

| Function | Type | Notes |
| --- | --- | --- |
| Impulse Storm | Button | Random shoves in the area, for the duration. |
| Gravity Roulette | Button | Random gravity per object, restored when it ends. |
| Material Shuffle | Button | Random materials, restored when it ends. |

### This mod's NPCs

| Function | Type | Notes |
| --- | --- | --- |
| All Follow Me | Button |  |
| Scatter | Button |  |
| Brawl | Button | Each armed NPC fights the next one. |
| Calm Down | Button |  |

### Saved sets

| Function | Type | Notes |
| --- | --- | --- |
| Saved Entity Sets | Section |  |

## Mod Tools (5)

### Cleaning up

| Function | Type | Notes |
| --- | --- | --- |
| Turn Off All Effects | Button |  |
| Turn Off Effects & Remove Everything Created | Button |  |

### Mod API

| Function | Type | Notes |
| --- | --- | --- |
| Mod API Browser | Section |  |
| System Commands & Arbitrary Files | **Unavailable** | Deliberately left out. Mods run in the ChaosScript sandbox, and this menu stays inside it. |

### Diagnostics

| Function | Type | Notes |
| --- | --- | --- |
| Build Diagnostic Report | Button |  |
| Diagnostic Report | Section |  |

## Profiles & Settings (10)

### Profiles

| Function | Type | Notes |
| --- | --- | --- |
| Active Profile | List |  |
| New Profile | Section |  |
| Delete This Profile | Button |  |

### Import & export

| Function | Type | Notes |
| --- | --- | --- |
| Export Current Settings | Button |  |
| Import Configuration | Section |  |

### Interface

| Function | Type | Notes |
| --- | --- | --- |
| Menu Size | Slider |  |

### Status

| Function | Type | Notes |
| --- | --- | --- |
| Reset All Settings | Button |  |

### Keys

| Function | Type | Notes |
| --- | --- | --- |
| Open or Close the Menu | Key | Default F6. |
| Select Under Crosshair | Key | Default F7. |
| Stop All Effects | Key | Default F8. |
