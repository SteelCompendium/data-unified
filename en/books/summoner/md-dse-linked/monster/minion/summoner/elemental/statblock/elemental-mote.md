---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: elemental-mote
file_dpath: monster/minion/summoner/elemental/statblock
flavor: This near-pure form of autonomous essence just barely maintains their form. They can shift their nature to match their surroundings.
free_strike: 1
immunities: []
intuition: 0
item_id: elemental-mote
item_name: Elemental Mote
keywords:
    - Elemental
might: 0
movement: Fly
name: Elemental Mote
organization: Minion
presence: 2
reason: 0
role: Hexer
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/elemental-mote
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: "1"
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: When the mote is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), each enemy adjacent to the mote has a [bane](../../../../../rule/dice/bane.md) on their next [strike](../../../../../rule/combat/strike.md).
      feature_type: trait
      icon: ⭐️
      name: Dweomer Burst
      type: feature
    - effects:
        - effect: |-
            Once per turn, the mote can transform into an adjacent allied [signature minion](../../../../../feature/summoner/level-1/minions.md), maintaining their current Stamina. The minion must be reassigned to a new squad if their new name differs from the other squad members.
            Alternatively, you can spend 1 essence to transform the mote into any [signature minion](../../../../../feature/summoner/level-1/minions.md) in the elemental portfolio you don't have, as if you summoned the new minion into the mote's space.
      feature_type: trait
      icon: ⭐️
      name: Catalyst
      type: feature
flavor: This near-pure form of autonomous essence just barely maintains their form. They can shift their nature to match their surroundings.
free_strike: 1
immunities: []
intuition: 0
keywords:
    - Elemental
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/elemental-mote
    source: mcdm.summoner.v1
might: 0
movement: Fly
name: Elemental Mote
organization: Minion
presence: 2
reason: 0
role: Hexer
size: 1T
speed: 5
stability: 0
stamina: "1"
type: statblock
weaknesses: []
```
