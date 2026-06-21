---
agility: 3
ev: "14"
free_strike: 6
immunities:
    - Fire 5
intuition: 1
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 5
might: 1
movement: Fly, hover
name: Hobgoblin Smokebinder
organization: Platoon
presence: 0
reason: 2
role: Ambusher
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-smokebinder
size: 1M
speed: 7
stability: 0
stamina: "70"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |             -              |      Level 5      |   Platoon Ambusher    |        EV 14         |
|:-------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|            **1M**<br>Size             |       **7**<br>Speed       | **70**<br>Stamina |  **0**<br>Stability   | **6**<br>Free Strike |
|        **Fire 5**<br>Immunity         | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+1**<br>Might            |     **+3**<br>Agility      | **+2**<br>Reason  |  **+1**<br>Intuition  |  **0**<br>Presence   |

> 🏹 **Choking Bolt (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 5**           | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 fire damage
> - **12-16:** 14 fire damage
> - **17+:** 17 fire damage; R < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** If this ability gains an edge or has a double edge, the target can't communicate with anyone until the end of their next turn.

> ❇️ **Smoke Bomb (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |                  **Maneuver** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes a Might test.
>
> - **≤11:** 11 damage; the target has a double bane on their next power roll
> - **12-16:** 9 damage; the target takes a bane on their next power roll
> - **17+:** 5 damage

> ⭐️ **Essence of Smoke**
>
> The smokebinder can move through spaces as if they were size 1T and can occupy another creature or object's space. At the end of their turn, the smokebinder can attempt to hide if they haven't taken any damage since their last turn.

> ⭐️ **Infernal Ichor**
>
> When the smokebinder is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the smokebinder takes 3 fire damage.
