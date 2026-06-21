---
agility: 3
ev: "32"
file_basename: voiceless-talker-evolutionist
file_dpath: monster/voiceless-talker/statblock
free_strike: 7
immunities:
    - Psychic 8
intuition: 1
item_id: voiceless-talker-evolutionist
item_name: Voiceless Talker Evolutionist
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: 0
movement: Hover, teleport
name: Voiceless Talker Evolutionist
organization: Leader
presence: 2
reason: 4
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/voiceless-talker-evolutionist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "180"
type: statblock
---

| Horror, Voiceless Talker  |                -                |      Level 6       |        Leader         |        EV 32         |
|:-------------------------:|:-------------------------------:|:------------------:|:---------------------:|:--------------------:|
|      **1M**<br>Size       |         **5**<br>Speed          | **180**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
| **Psychic 8**<br>Immunity | **Hover, teleport**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|      **0**<br>Might       |        **+3**<br>Agility        |  **+4**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> ⚔️ **Psionic Intrusion ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Psionic, Ranged, Strike** |                 **Main action** |
> |------------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 5**         | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 psychic damage; R < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 16 psychic damage; R < 3 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 19 psychic damage; R < 4 [slowed](../../../condition/slowed.md) (save ends)

> 🏹 **Carpe Quadratum**
>
> | **Psionic, Ranged** |        **Maneuver** |
> |---------------------|--------------------:|
> | **📏 Ranged 5**     | **🎯 One creature** |
>
> **Effect:** The evolutionist [teleports](../../../movement/teleport.md) to swap places with the target.

> ❗️ **Adaptability**
>
> | **Psionic** | **[Triggered Action](../../../rule/combat/triggered-action.md)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The evolutionist takes damage that has a damage type.
>
> **Effect:** Until the start of their next turn, the evolutionist has damage immunity 5 to the triggering damage type.

> ⭐️ **[End Effect](../../../rule/monster/end-effect.md)**
>
> At the end of each of their turns, the evolutionist can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.

> ⭐️ **Witness Evolutionary Superiority**
>
> The evolutionist has any trait of the Director's choice from any ally [minion](../../../rule/organization/minion.md) in the encounter.

> ☠️ **Show Me Who You Are ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Psionic**     |               **-** |
> |-----------------------------|------------------------------:|
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes an Intuition test.
>
> - **≤11:** The target uses a [signature ability](../../../rule/combat/signature-ability.md) against the nearest enemy within distance.
> - **12-16:** The target makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the nearest enemy within distance.
> - **17+:** [Frightened](../../../condition/frightened.md) (save ends)

> ☠️ **Release the Thralls ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Psionic, Ranged** |          **-** |
> |---------------------|---------------:|
> | **📏 Ranged 5**     | **🎯 Special** |
>
> **Effect:** The evolutionist [teleports](../../../movement/teleport.md) eight [minions](../../../rule/organization/minion.md) of level 4 or lower into unoccupied spaces within distance. All eight [minions](../../../rule/organization/minion.md) can be of any monster type but must share the same name.

> ☠️ **Brainstorm ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Psionic** |                         **-** |
> |-------------------|------------------------------:|
> | **📏 3 burst**    | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 lightning damage
> - **12-16:** 12 lightning damage
> - **17+:** 15 lightning damage
>
> **Effect:** Until the end of the encounter, the evolutionist is surrounded by a psionic electrical storm that is a 5 aura. The area is [difficult terrain](../../../movement/difficult-terrain.md) for enemies, and any enemy who enters the area for the first time in a round or starts their turn there takes 8 lightning damage.
