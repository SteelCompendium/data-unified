---
agility: 1
ev: '-'
file_basename: troll-mercenary
file_dpath: monster/retainer/statblock
free_strike: 6
intuition: 0
item_id: troll-mercenary
item_name: Troll Mercenary
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Mercenary
organization: Retainer
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.retainer.statblock/troll-mercenary
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 4
stamina: "57"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

|   Giant, Troll    |         -          |      Level 5      |    Brute Retainer     |              EV -               |
|:-----------------:|:------------------:|:-----------------:|:---------------------:|:-------------------------------:|
|   **2**<br>Size   |   **6**<br>Speed   | **57**<br>Stamina |  **4**<br>Stability   |      **6**<br>Free Strike       |
| **-**<br>Immunity | **- **<br>Movement |         -         | **-**<br>With Captain |  **Acid 5, fire **<br>Weakness  |
|  **+3**<br>Might  | **+1**<br>Agility  | **-1**<br>Reason  |  **0**<br>Intuition   |       **+1**<br>Presence        |

> 🗡 **Big Bite (Signature Ability)**
>
> | **Charge, Melee, Strike, Weapon** |               **Main action** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 1**                    | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage
> - **12-16:** 11 damage
> - **17+:** 14 damage
>
> **Effect:** The mercenary regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to half the damage dealt.

> ❇️ **Troll Roar (Encounter)**
>
> | **Area**       |                  **Maneuver** |
> |----------------|------------------------------:|
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** P < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **12-16:** P < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends), push 3, [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> ⭐️ **Relentless Hunger**
>
> The mercenary dies only if they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by acid or fire damage, if they end their turn with 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), or if they take acid or fire damage while at 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
