---
agility: 5
ev: "36"
free_strike: 7
immunities:
    - Corruption 9
    - poison 9
intuition: 1
keywords:
    - Undead
    - Vampire
level: 7
might: 2
movement: Climb, hover, teleport
name: Vampire Lord
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire-lord
size: 1M
speed: 12
stability: 3
stamina: "200"
type: statblock
---

|            Undead, Vampire             |                   -                    |       Level 7       |        Leader         |        EV 36         |
|:--------------------------------------:|:--------------------------------------:|:-------------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |             **12**<br>Speed            | **200**<br>Stamina  |  **3**<br>Stability   | **7**<br>Free Strike |
| **Corruption 9, poison 9**<br>Immunity | **Climb, hover, teleport**<br>Movement |          -          | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+2**<br>Might             |           **+5**<br>Agility            |  **+1**<br>Reason   |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Crimson Embrace ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |     **[Main action](../../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 5:**
>
> - **≤11:** 13 corruption damage; M < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
> - **12-16:** 21 corruption damage; M < 4 [bleeding](../../../../condition/bleeding.md) (save ends)
> - **17+:** 24 corruption damage; M < 5 [bleeding](../../../../condition/bleeding.md) (save ends)
>
> **Effect:** The vampire regains [Stamina](../../../../rule/health/stamina.md) equal to half the damage dealt, and can end one effect on them that can be ended by a [saving throw](../../../../rule/general/saving-throw.md).
>
> **2+ [Malice](../../../../rule/monster/malice.md):** The vampire [shifts](../../../../movement/shifting.md) 3 after striking the last target, and can target one additional creature for every 2 malice spent.

> 🏹 **Arise, My Children (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Ranged**       |   **[Maneuver](../../../../rule/combat/turn.md)** |
> |------------------|---------------:|
> | **📏 Ranged 10** | **🎯 Special** |
>
> **Effect:** Two blood-starved vampires appear in unoccupied spaces within distance.

> ❗️ **Redirected Charm (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** | **Free [triggered action](../../../../rule/combat/triggered-action.md)** |
> |-------------------|--------------------------:|
> | **📏 Ranged 5**   |          **🎯 One enemy** |
>
> **Trigger:** A creature makes a [strike](../../../../rule/combat/strike.md) against the vampire.
>
> **Effect:** The target becomes the new target of the [strike](../../../../rule/combat/strike.md).

> ⭐️ **Lord's Bloodthirst**
>
> The vampire has speed 15 and an [edge](../../../../rule/dice/edge.md) on power rolls while any creature within 20 squares of them is [bleeding](../../../../condition/bleeding.md). Any [bleeding](../../../../condition/bleeding.md) creature within 5 squares of the vampire can't hide.

> ☠️ **Let Us Feast! ([Villain Action](../../../../rule/monster/villain-action.md) 1)**
>
> | **Ranged**      |                         **-** |
> |-----------------|------------------------------:|
> | **📏 20 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target who has P < 4 is now [bleeding](../../../../condition/bleeding.md) (save ends).

> ☠️ **Red Mist Rising ([Villain Action](../../../../rule/monster/villain-action.md) 2)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 2 damage; M < 3 6 corruption damage
> - **12-16:** 7 damage; M < 4 6 corruption damage
> - **17+:** 10 damage; M < 5 6 corruption damage
>
> **Effect:** The vampire turns to mist, filling the area. Until the end of the round, the vampire can't move or be targeted by abilities, but they can use Crimson Embrace against a target in the area. The vampire reforms in an unoccupied space in the area at the end of the round.

> ☠️ **Sacrifice ([Villain Action](../../../../rule/monster/villain-action.md) 3)**
>
> | **Magic, Ranged** |                   **-** |
> |-------------------|------------------------:|
> | **📏 Ranged 20**  | **🎯 Each chosen ally** |
>
> **Effect:** Each target is marked for sacrifice. At the end of the round, each target who isn't dead or destroyed takes 50 corruption damage. The vampire then uses the following ability.
>
> **Wave of Blood:**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 20 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes a **Might test**. This ability deals an extra 5 damage for each creature killed by the Sacrifice [villain action](../../../../rule/monster/villain-action.md).
>
> - **≤11:** 11 corruption damage
> - **12-16:** 8 corruption damage
> - **17+:** 2 corruption damage
