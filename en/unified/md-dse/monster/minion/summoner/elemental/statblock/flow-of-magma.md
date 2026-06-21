---
agility: -2
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: flow-of-magma
file_dpath: monster/minion/summoner/elemental/statblock
flavor: This elemental is a long, serpentine creature of heated rock. Flows of magma drool trails of lava from their fangs after biting their prey.
free_strike: 4
immunities:
    - Fire R
intuition: 0
item_id: flow-of-magma
item_name: Flow of Magma
keywords:
    - Elemental (Fire)
    - Elemental (Earth)
might: 2
movement: Climb
name: Flow of Magma
organization: Minion
presence: 1
reason: 0
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/flow-of-magma
size: 1L
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: 6 | 6
type: statblock
weaknesses:
    - —
---

This elemental is a long, serpentine creature of heated rock. Flows of magma drool trails of lava from their fangs after biting their prey.

| Elemental (Fire, Earth) | - | - | Minion Harrier | 3 essence for two minions |
|:-------------:|:-----------------------:|:--------------:|:-:|:-------------------------:|
| **1L**<br>Size | **5**<br>Speed | **6 \| 6**<br>Stamina | **2**<br>Stability | **4**<br>Free Strike |
| **Fire R**<br>Immunity | **Climb**<br>Movement | - | **—**<br>Weakness | **Fire**<br>Free Strike Damage Type |
| **+2**<br>Might | **-2**<br>Agility | **0**<br>Reason | **0**<br>Intuition | **+1**<br>Presence |

> 🏹 **Molten Strike 2d10 + R (Signature Ability)**
>
> | **Magic, Melee, Strike** | **Main action** |
> |--------------------------|----------------:|
> | **📏 Melee 2** | **🎯 One creature or object per minion** |
>
> 4 fire damage; [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 3
>
> 6 fire damage; [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 4
>
> 8 fire damage; [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 5
>
> **Effect:** Each square that the flow [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) into becomes wreathed in flames until the start of the flow's next turn. An enemy that enters an affected square takes 2 damage.

> ⭐️ **Eruption** 1 Essence
>
> When the flow is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they launch lava into an area equal to 1 + their size within 5 squares. The affected area becomes [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies until the end of the encounter. An enemy that enters an affected square or starts their turn there takes A < AVERAGE 4 fire damage.
