---
agility: 2
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: ceaseless-mournling
file_dpath: monster/minion/summoner/undead/statblock
flavor: Mournlings are hulking amalgams of mismatched cadavers with tear-stained trenches where their cheeks used to be. Their crying shakes enemies to their bone and renders them struggling to move.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 1
item_id: ceaseless-mournling
item_name: Ceaseless Mournling
keywords:
    - Undead
might: 3
movement: Burrow
name: Ceaseless Mournling
organization: Minion
presence: -2
reason: -1
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/ceaseless-mournling
size: "2"
source: mcdm.summoner.v1
speed: 4
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: At the end of the mournling's [turn](../../../../../rule/combat/turn.md), each enemy within 1 of the mournling takes 2 sonic [damage](../../../../../rule/damage/damage.md) and can't [shift](../../../../../movement/shifting.md) until the start of the mournling's next [turn](../../../../../rule/combat/turn.md).
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
        - effect: The first time the mournling [burrows](../../../../../movement/burrow.md) out of the ground on their [turn](../../../../../rule/combat/turn.md), they can make a [free strike](../../../../../feature/common/main-actions/free-strike.md) against each [adjacent](../../../../../rule/combat/adjacent.md) enemy.
      feature_type: trait
      icon: ⭐️
      name: Rupture
      type: feature
flavor: Mournlings are hulking amalgams of mismatched cadavers with tear-stained trenches where their cheeks used to be. Their crying shakes enemies to their bone and renders them struggling to move.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 1
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/ceaseless-mournling
    source: mcdm.summoner.v1
might: 3
movement: Burrow
name: Ceaseless Mournling
organization: Minion
presence: -2
reason: -1
role: Controller
size: "2"
speed: 4
stability: 0
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
```
