---
agility: 2
ev: "32"
file_basename: hobgoblin-bloodlord
file_dpath: monster/hobgoblin/statblock
free_strike: 7
immunities:
    - Fire 6
intuition: 3
item_id: hobgoblin-bloodlord
item_name: Hobgoblin Bloodlord
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
might: 4
movement: Teleport
name: Hobgoblin Bloodlord
organization: Leader
presence: 3
reason: 2
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-bloodlord
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "180"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |            -             |      Level 6       |        Leader         |        EV 32         |
|:-------------------------------------:|:------------------------:|:------------------:|:---------------------:|:--------------------:|
|            **1M**<br>Size             |      **6**<br>Speed      | **180**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
|        **Fire 6**<br>Immunity         | **Teleport**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+4**<br>Might            |    **+2**<br>Agility     |  **+2**<br>Reason  |  **+3**<br>Intuition  |  **+3**<br>Presence  |

> 🗡 **Soul Sword (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |                 **Main action** |
> |----------------------------------|--------------------------------:|
> | **📏 Melee 1**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 corruption damage; P < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 16 corruption damage; P < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 19 corruption damage; P < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each target is marked until the end of the encounter or until they die. The bloodlord's allies gain an edge on strikes against any target marked this way. The bloodlord can have up to three targets marked this way. If they mark a new target who would exceed the limit, the oldest mark ends.

> 🏹 **Take Point!**
>
> | **Ranged**       |    **Maneuver** |
> |------------------|----------------:|
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a signature ability.

> ❗️ **An Army From Blood (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Ranged**       |           **Triggered action** |
> |------------------|-------------------------------:|
> | **📏 Ranged 10** | **🎯 The triggering creature** |
>
> **Trigger:** A non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) hobgoblin within distance takes damage.
>
> **Effect:** Three hobgoblin recruits manifest from the target's blood into unoccupied spaces [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target.

> ⭐️ **Infernal Ichor**
>
> When the bloodlord is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the bloodlord takes 3 fire damage.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the bloodlord can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

> ☠️ **Advance! ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**        |                                 **-** |
> |-----------------|--------------------------------------:|
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target gains 10 temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and can move up to their speed. Then each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) target can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).

> ☠️ **Skulls Abound ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area, Magic** |       **-** |
> |-----------------|------------:|
> | **📏 3 aura**   | **🎯 Self** |
>
> **Effect:** Until the end of the encounter, the bloodlord surrounds themself with a storm of flying skulls. Any enemy who enters the area for the first time in a round or starts their turn there takes 8 corruption damage and takes a bane on their next power roll until the start of their next turn.

> ☠️ **I Am Fire! I Am Death! ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 5 fire damage; P < 2 2 fire damage, [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 5 fire damage; P < 3 7 fire damage, [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 5 fire damage; P < 4 10 fire damage, [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **Effect:** Until the end of the encounter, the bloodlord is wreathed in black flames. Whenever any [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy [grabs](scc.v1:mcdm.heroes.v1/condition/grabbed) the bloodlord or uses a melee ability against them, that enemy takes 5 corruption damage.
