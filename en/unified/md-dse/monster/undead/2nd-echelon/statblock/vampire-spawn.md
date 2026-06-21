---
agility: 3
ev: "6"
file_basename: vampire-spawn
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 1
item_id: vampire-spawn
item_name: Vampire Spawn
keywords:
    - Undead
    - Vampire
level: 4
might: 2
movement: Climb
name: Vampire Spawn
organization: Horde
presence: 2
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/vampire-spawn
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

|            Undead, Vampire             |           -           |      Level 4      |     Horde Harrier     |         EV 6         |
|:--------------------------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |    **5**<br>Speed     | **30**<br>Stamina |  **0**<br>Stability   | **2**<br>Free Strike |
| **Corruption 4, poison 4**<br>Immunity | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+2**<br>Might             |   **+3**<br>Agility   | **-1**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Exsanguinating Bite ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage
> - **12-16:** 7 corruption damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 9 corruption damage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** The vampire spawn regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to any corruption damage dealt.
>
> **1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The target takes an additional 3 corruption damage.

> 👤 **Vampiric Celerity**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The vampire spawn can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square, then move up to their speed. The next ability the vampire uses before the start of their next turn gains an edge.

> ⭐️ **Unslakable Bloodthirst**
>
> The vampire spawn has speed 10 while any creature within 10 squares of them is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding). The vampire spawn must use Exsanguinating Bite against a [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) creature on their turn if they are able to.
