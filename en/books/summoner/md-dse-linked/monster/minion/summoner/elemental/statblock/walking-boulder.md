---
agility: -2
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: walking-boulder
file_dpath: monster/minion/summoner/elemental/statblock
flavor: These massive clods of animated stone roll upon smaller piles of rocks that could be perceived as limbs. Walking boulders are useful for taking up space and forming barricades.
free_strike: 1
immunities: []
intuition: 0
item_id: walking-boulder
item_name: Walking Boulder
keywords:
    - Elemental (Earth)
might: 2
movement: Climb
name: Walking Boulder
organization: Minion
presence: 1
reason: 0
role: Defender
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/walking-boulder
size: "2"
source: mcdm.summoner.v1
speed: 4
stamina: "3"
type: statblock
weaknesses: []
---

```ds-sb
agility: -2
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: The boulder obstructs [line of effect](../../../../../rule/combat/line-of-effect.md) for enemies.
      feature_type: trait
      icon: ⭐️
      name: Obstruct
      type: feature
    - cost: 1 Essence
      effects:
        - effect: When one or more boulders is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they each leave behind a stone [wall](../../../../../rule/combat/wall.md) equal to their size in their space until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Pile Up
      type: feature
flavor: These massive clods of animated stone roll upon smaller piles of rocks that could be perceived as limbs. Walking boulders are useful for taking up space and forming barricades.
free_strike: 1
immunities: []
intuition: 0
keywords:
    - Elemental (Earth)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/walking-boulder
    source: mcdm.summoner.v1
might: 2
movement: Climb
name: Walking Boulder
organization: Minion
presence: 1
reason: 0
role: Defender
size: "2"
speed: 4
stability: 0
stamina: "3"
type: statblock
weaknesses: []
```
