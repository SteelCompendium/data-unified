---
agility: -2
ev: "48"
file_basename: servok-war-engine
file_dpath: monster/valok/statblock
free_strike: 10
intuition: -1
item_id: servok-war-engine
item_name: Servok War Engine
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 10
might: 5
name: Servok War Engine
organization: Elite
presence: -5
reason: -4
role: Brute
scc: mcdm.monsters.v1/monster.valok.statblock/servok-war-engine
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 8
stamina: "260"
type: statblock
---

| Construct, Servok, Soulless, Valok |         -         |      Level 10       |      Elite Brute      |         EV 48         |
|:----------------------------------:|:-----------------:|:-------------------:|:---------------------:|:---------------------:|
|           **3**<br>Size            |  **5**<br>Speed   | **260**<br>Stamina  |  **8**<br>Stability   | **10**<br>Free Strike |
|         **-**<br>Immunity          | **-**<br>Movement |          -          | **-**<br>With Captain |   **-**<br>Weakness   |
|          **+5**<br>Might           | **-2**<br>Agility |  **-4**<br>Reason   |  **-1**<br>Intuition  |   **-5**<br>Presence  |

> 🗡 **Blade Rake ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage
> - **12-16:** 21 damage; [pull](../../../movement/forced-movement.md) 3
> - **17+:** 25 damage; [pull](../../../movement/forced-movement.md) 6

> 🏹 **Prismacore Cannon**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 20**           | **🎯 One creature or object** |
>
> **Power Roll + 5:**
>
> - **≤11:** 22 damage
> - **12-16:** 29 damage; I < 4 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 34 damage; I < 5 [dazed](../../../condition/dazed.md) (save ends)
>
> **Effect:** This damage can't be reduced in any way. This ability can't be used again until the start of the next round.

> 👤 **Destructive Rollout**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The war engine moves up to their speed in a straight line, automatically destroying mundane size 1 objects or walls in their path. The first time the war engine moves through a creature's space during this movement, that creature can choose to either fall [prone](../../../condition/prone.md) or take 10 damage.

> 🔳 **Burning Oil (3 Malice)**
>
> | **Area**                    |                             **Maneuver** |
> |-----------------------------|-----------------------------------------:|
> | **📏 20 x 1 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 16 fire damage; the target is burning (save ends)
> - **12-16:** 12 fire damage; the target is burning (EoT)
> - **17+:** 8 fire damage
>
> A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. Additionally, the area is burning until the end of the encounter. While the area is burning, it is [difficult terrain](../../../movement/difficult-terrain.md) and any enemy takes 3 fire damage for each square of the area they enter.

> ❗️ **Quick Blast (1 Malice)**
>
> | **Ranged, Strike, Weapon** |     **Free triggered action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 20**           | **🎯 One creature or object** |
>
> **Trigger:** The target deals damage to the war engine.
>
> **Power Roll + 5:**
>
> - **≤11:** 8 damage; [push](../../../movement/forced-movement.md) 2
> - **12-16:** 12 damage; [push](../../../movement/forced-movement.md) 5
> - **17+:** 16 damage; [push](../../../movement/forced-movement.md) 8
>
> **Effect:** This damage can't be reduced in any way.

> ⭐️ **Servok Siege Machine**
>
> The war engine ignores [difficult terrain](../../../movement/difficult-terrain.md), and their abilities deal an extra 15 damage to objects.

> ⭐️ **Crafted to Perfection**
>
> The war engine's shape can't be changed by any external effect.

> ⭐️ **Valiar Might**
>
> While the war engine isn't [bleeding](../../../condition/bleeding.md), [weakened](../../../condition/weakened.md), or [winded](../../../rule/health/winded.md), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
