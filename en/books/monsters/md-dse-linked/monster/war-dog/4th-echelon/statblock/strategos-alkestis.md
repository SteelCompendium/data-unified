---
agility: 4
ev: "48"
file_basename: strategos-alkestis
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 10
intuition: 5
item_id: strategos-alkestis
item_name: Strategos Alkestis
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 4
name: Strategos Alkestis
organization: Leader
presence: 5
reason: 5
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/strategos-alkestis
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "260"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 10       |        Leader         |        EV 48         |
|:---------------------------:|:-----------------:|:-------------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |  **5**<br>Speed   | **260**<br>Stamina |  **2**<br>Stability   | **10**<br>Free Strike |
|      **-**<br>Immunity      | **-**<br>Movement |          -          | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+4**<br>Might       | **+4**<br>Agility |  **+5**<br>Reason   |  **+5**<br>Intuition  |  **+5**<br>Presence  |

> ⚔️ **Houndgun and Houndblade ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Ranged, Strike, Weapon** |                 **Main action** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 10**       | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage; M < 4 [bleeding](../../../../condition/bleeding.md) (save ends)
> - **12-16:** 21 damage; M < 5 [bleeding](../../../../condition/bleeding.md) (save ends)
> - **17+:** 25 damage; M < 6 [bleeding](../../../../condition/bleeding.md) (save ends)
>
> **Effect:** Each target loses 1d3 Recoveries.
>
> **2 [Malice](../../../../rule/monster/malice.md):** When a target is made [bleeding](../../../../condition/bleeding.md) this way, each ally [adjacent](../../../../rule/combat/adjacent.md) to them can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against the target.

> 🏹 **Focus Fire**
>
> | **Ranged**       |                  **Maneuver** |
> |------------------|------------------------------:|
> | **📏 Ranged 15** | **🎯 One creature or object** |
>
> **Effect:** Until the start of Alkestis's next turn, any effect that reduces the damage taken by the target has no effect.

> ❗️ **Artillery Enfilade (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area, Ranged, Weapon**    |                        **Triggered action** |
> |-----------------------------|--------------------------------------------:|
> | **📏 7 x 3 line within 10** | **🎯 Each creature and object in the area** |
>
> **Trigger:** An ally is reduced to 0 [Stamina](../../../../rule/health/stamina.md) within 10 squares of Alkestis.
>
> **Power Roll + 5:**
>
> - **≤11:** 8 damage; A < 4 [slowed](../../../../condition/slowed.md) (save ends)
> - **12-16:** 13 damage; A < 5 [slowed](../../../../condition/slowed.md) (save ends)
> - **17+:** 16 damage; A < 6 [slowed](../../../../condition/slowed.md) (save ends)
>
> **Effect:** The area is [difficult terrain](../../../../movement/difficult-terrain.md) until the start of the next round.

> ⭐️ **[End Effect](../../../../rule/monster/end-effect.md)**
>
> At the end of each of her turns, Alkestis can take 20 damage to end one effect on her that can be ended by a [saving throw](../../../../rule/general/saving-throw.md). This damage can't be reduced in any way.

> ⭐️ **Tactical Brilliance**
>
> At the start of each of Alkestis's turns, the Director gains 2 [Malice](../../../../rule/monster/malice.md). While Alkestis is alive and in the encounter, the Director also gains 1 [Malice](../../../../rule/monster/malice.md) whenever a war dog in the encounter obtains a tier 3 outcome on a power roll.

> ☠️ **Fog of War ([Villain Action](../../../../rule/monster/villain-action.md) 1)**
>
> | **-**          |                             **-** |
> |----------------|----------------------------------:|
> | **📏 Special** | **🎯 Each ally in the encounter** |
>
> **Effect:** Each target can disappear, then reappear anywhere on the encounter map 3 or more squares away from any enemy. Additionally, each target has a double edge on their next power roll.

> ☠️ **Send in the Second Wave ([Villain Action](../../../../rule/monster/villain-action.md) 2)**
>
> | **Ranged**       |          **-** |
> |------------------|---------------:|
> | **📏 Ranged 15** | **🎯 Special** |
>
> **Effect:** For each war dog reduced to 0 [Stamina](../../../../rule/health/stamina.md) in the encounter, a war dog shriketrooper appears in an unoccupied space within distance.

> ☠️ **The Silver Wolf's Final Stratagem ([Villain Action](../../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Magic** |                            **-** |
> |-----------------|---------------------------------:|
> | **📏 5 burst**  | **🎯 Each creature in the area** |
>
> **Effect:** Until the start of the next round, each target enemy who has I < 4 is [dazed](../../../../condition/dazed.md), each target enemy who has M < 4 is [restrained](../../../../condition/restrained.md), and each target enemy who has A < 4 can't use [triggered actions](../../../../rule/combat/triggered-action.md). Additionally, until the end of the encounter, Alkestis and each target ally have damage immunity 3 and deal an extra 5 damage with strikes.
