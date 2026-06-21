---
agility: 5
ev: "144"
file_basename: count-rhodar-von-glauer
file_dpath: monster/count-rhodar-von-glauer/statblock
free_strike: 10
immunities:
    - Corruption 10
    - poison 10
intuition: 2
item_id: count-rhodar-von-glauer
item_name: Count Rhodar von Glauer
keywords:
    - Undead
    - Vampire
level: 10
might: 3
movement: Fly, hover, teleport
name: Count Rhodar von Glauer
organization: Solo
presence: 3
reason: 2
scc: mcdm.monsters.v1/monster.count-rhodar-von-glauer.statblock/count-rhodar-von-glauer
size: 1M
source: mcdm.monsters.v1
speed: 12
stability: 3
stamina: "650"
type: statblock
---

|             Undead, Vampire              |                  -                   |       Level 10       |         Solo          |        EV 144         |
|:----------------------------------------:|:------------------------------------:|:--------------------:|:---------------------:|:---------------------:|
|              **1M**<br>Size              |            **12**<br>Speed           |  **650**<br>Stamina  |  **3**<br>Stability   | **10**<br>Free Strike |
| **Corruption 10, poison 10**<br>Immunity | **Fly, hover, teleport**<br>Movement |          -           | **-**<br>With Captain |   **-**<br>Weakness   |
|             **+3**<br>Might              |          **+5**<br>Agility           |   **+2**<br>Reason   |  **+2**<br>Intuition  |   **+3**<br>Presence  |

> ☠️ **Solo Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of his turns, Rhodar can take 20 damage to end one effect on him that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
>
> **Solo Turns:** Rhodar can take two turns each round. He can't take turns consecutively.

> ⭐️ **Grave Ward**
>
> Rhodar has damage immunity 5. If he takes holy damage, he loses this immunity until the end of the round.

> ⭐️ **Thin the Blood**
>
> Each enemy within 10 squares of Rhodar takes a -2 penalty to [saving throws](../../../rule/general/saving-throw.md).

> ⚔️ **Spear of the Damned ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Magic, Melee, Ranged, Strike, Weapon** |                   **Main action** |
> |------------------------------------------|----------------------------------:|
> | **📏 Melee 2 or ranged 15**              | **🎯 Three creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 13 damage; A < 4 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** 18 damage; A < 5 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 21 damage; A < 6 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** A target [restrained](../../../condition/restrained.md) this way is impaled by a spear. Rhodar has four spears, each of which can be used to impale a target. At the start of each of his turns, Rhodar can summon any of his spears back to himself, ending the [restrained](../../../condition/restrained.md) condition on an impaled target.

> ❇️ **Disarming Glare**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes an Intuition test.
>
> - **≤11:** 16 corruption damage; [frightened](../../../condition/frightened.md) (save ends)
> - **12-16:** 13 corruption damage; [frightened](../../../condition/frightened.md) (EoT)
> - **17+:** 8 corruption damage
>
> While a target is [frightened](../../../condition/frightened.md) this way, Rhodar ignores banes and double banes on abilities used against them.

> 🗡 **Vermilion Fangs (3 Malice)**
>
> | **Melee, Weapon, Strike** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 5:**
>
> - **≤11:** 17 corruption damage; M < 4 [bleeding](../../../condition/bleeding.md) (save ends) and [prone](../../../condition/prone.md)
> - **12-16:** 24 corruption damage; [prone](../../../condition/prone.md); M < 5 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 30 corruption damage; [prone](../../../condition/prone.md); M < 6 the target is [bleeding](../../../condition/bleeding.md) until the end of the encounter
>
> **Effect:** Rhodar regains [Stamina](../../../rule/health/stamina.md) equal to half the damage dealt.

> ❇️ **Sanguineous Flourish (5 Malice)**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 2 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 6 damage, 2 corruption damage; [push](../../../movement/forced-movement.md) 2; M < 4 [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 6 damage, 7 corruption damage; [push](../../../movement/forced-movement.md) 5; M < 5 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 6 damage, 10 corruption damage; [push](../../../movement/forced-movement.md) 7; M < 6 [bleeding](../../../condition/bleeding.md) (save ends)
>
> **Effect:** Rhodar [shifts](../../../movement/shifting.md) up to his speed before or after using this ability. He regains [Stamina](../../../rule/health/stamina.md) equal to half the total corruption damage dealt.

> 🔳 **Vengeance of Rhöl (2 Malice)**
>
> | **Area, Magic, Ranged**     |   **Maneuver** |
> |-----------------------------|---------------:|
> | **📏 Two 3 cubes within 5** | **🎯 Special** |
>
> **Effect:** Each area is saturated with vengeful spirits until the end of the round. Any enemy who enters the area for the first time in a round or starts their turn there takes 5 corruption damage. At the end of the round, the spirits violently disperse. Each enemy within 2 squares of an area and has P < 5 is [weakened](../../../condition/weakened.md) (save ends).

> ❗️ **Reactive Rebuke (2 Malice)**
>
> | **Magic, Ranged** |           **[Triggered Action](../../../rule/combat/triggered-action.md)** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 10**  | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance makes a strike against Rhodar.
>
> **Effect:** A target who has I < 5 is [frightened](../../../condition/frightened.md). This effect ends if the target is 11 or more squares from Rhodar.

> ⭐️ **Lord's Bloodthirst**
>
> Rhodar has speed 15 and an edge on power rolls while any creature within 20 squares of him is [bleeding](../../../condition/bleeding.md). Any [bleeding](../../../condition/bleeding.md) creature within 10 squares of Rhodar can't hide.

> ☠️ **Red Tide ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Magic, Ranged** |                         **-** |
> |-------------------------|------------------------------:|
> | **📏 8 cube within 15** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 corruption damage; A < 4 the target is blood soaked (save ends)
> - **12-16:** 13 corruption damage; A < 5 the target is blood soaked (save ends)
> - **17+:** 16 corruption damage; A < 6 the target is blood soaked until the end of the encounter
>
> **Effect:** While a creature is blood soaked, Rhodar has a double edge on abilities used against them.

> ☠️ **Sanguine Mist ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes a Presence test.
>
> - **≤11:** 16 corruption damage; the target is [bleeding](../../../condition/bleeding.md) until the end of the encounter
> - **12-16:** 13 corruption damage; [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 8 corruption damage
>
> **Effect:** Rhodar [teleports](../../../movement/teleport.md) to an unoccupied space in the area. If he has lost the damage immunity from his Grave Ward trait, he regains it.

> ☠️ **Fires of Dracul ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Magic**             |                         **-** |
> |-----------------------------|------------------------------:|
> | **📏 15 x 3 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 10 fire damage; R < 4 [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 16 fire damage; R < 5 [weakened](../../../condition/weakened.md) (save ends)
> - **17+:** 20 fire damage; R < 6 [weakened](../../../condition/weakened.md) (save ends)
>
> **Effect:** Rhodar [teleports](../../../movement/teleport.md) to an unoccupied space [adjacent](../../../rule/combat/adjacent.md) to one target after the ability resolve.
