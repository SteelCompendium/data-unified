---
agility: 3
ev: "32"
free_strike: 7
immunities:
    - Psychic 8
intuition: 1
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

> ⚔️ **Psionic Intrusion ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Psionic, Ranged, Strike** |                 **Main action** |
> |------------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 5**         | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 psychic damage; R < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 16 psychic damage; R < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 19 psychic damage; R < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

> 🏹 **Carpe Quadratum**
>
> | **Psionic, Ranged** |        **Maneuver** |
> |---------------------|--------------------:|
> | **📏 Ranged 5**     | **🎯 One creature** |
>
> **Effect:** The evolutionist [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to swap places with the target.

> ❗️ **Adaptability**
>
> | **Psionic** | **[Triggered Action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The evolutionist takes damage that has a damage type.
>
> **Effect:** Until the start of their next turn, the evolutionist has damage immunity 5 to the triggering damage type.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the evolutionist can take 10 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ⭐️ **Witness Evolutionary Superiority**
>
> The evolutionist has any trait of the Director's choice from any ally [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) in the encounter.

> ☠️ **Show Me Who You Are ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area, Psionic**     |               **-** |
> |-----------------------------|------------------------------:|
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes an Intuition test.
>
> - **≤11:** The target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the nearest enemy within distance.
> - **12-16:** The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the nearest enemy within distance.
> - **17+:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)

> ☠️ **Release the Thralls ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Psionic, Ranged** |          **-** |
> |---------------------|---------------:|
> | **📏 Ranged 5**     | **🎯 Special** |
>
> **Effect:** The evolutionist [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) eight [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) of level 4 or lower into unoccupied spaces within distance. All eight [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) can be of any monster type but must share the same name.

> ☠️ **Brainstorm ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
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
> **Effect:** Until the end of the encounter, the evolutionist is surrounded by a psionic electrical storm that is a 5 aura. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies, and any enemy who enters the area for the first time in a round or starts their turn there takes 8 lightning damage.
