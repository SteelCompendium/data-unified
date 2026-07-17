---
agility: 4
cost: 4 Malice for three minions
cost_amount: "4"
cost_resource: Malice for three minions
file_basename: ceaseless-mournling
file_dpath: monster/rival/3rd-echelon/summoner/minion/statblock
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 3
item_id: ceaseless-mournling
item_name: Ceaseless Mournling
keywords:
    - Undead
might: 4
movement: Burrow
name: Ceaseless Mournling
organization: Minion
presence: 0
reason: 1
role: Controller
scc: mcdm.summoner.v1/monster.rival.3rd-echelon.summoner.minion.statblock/ceaseless-mournling
size: "2"
source: mcdm.summoner.v1
speed: 5
stability: 4
stamina: 8 | 8 | 8
type: statblock
weaknesses: []
---

```ds-sb
agility: 4
cost: 4 Malice for three minions
ev: ""
features:
    - effects:
        - effect: At the end of the mournling's turn, each enemy within 1 of the mournling takes 2 sonic damage and can't [shift](../../../../../../movement/shifting.md) until the start of the mournling's next turn.
      feature_type: trait
      icon: ⭐️
      name: Always Crying
      type: feature
    - effects:
        - effect: The mournling's shape can't change via any external effects.
      feature_type: trait
      icon: ⭐️
      name: Immutable Form
      type: feature
    - effects:
        - effect: The first time the mournling [burrows](../../../../../../movement/burrow.md) out of the ground on their turn, they can make a [free strike](../../../../../../feature/common/main-actions/free-strike.md) against each [adjacent](../../../../../../rule/combat/adjacent.md) enemy.
      feature_type: trait
      icon: ⭐️
      name: Rupture
      type: feature
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 3
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.3rd-echelon.summoner.minion.statblock/ceaseless-mournling
    source: mcdm.summoner.v1
might: 4
movement: Burrow
name: Ceaseless Mournling
organization: Minion
presence: 0
reason: 1
role: Controller
size: "2"
speed: 5
stability: 4
stamina: 8 | 8 | 8
type: statblock
weaknesses: []
```
