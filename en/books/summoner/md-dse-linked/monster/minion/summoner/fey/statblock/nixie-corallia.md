---
agility: 3
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: nixie-corallia
file_dpath: monster/minion/summoner/fey/statblock
flavor: Corallias are saltwater nixies with coarse, coral-like skin and curly hair with hooked ends. Their salty tears are used to hallow places of worship and ward off demons.
free_strike: 7
free_strike_damage_type: Lightning
immunities:
    - Lightning R
intuition: 4
item_id: nixie-corallia
item_name: Nixie Corallia
keywords:
    - Fey
might: -2
movement: Swim
name: Nixie Corallia
organization: Minion
presence: 1
reason: 3
role: Support
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-corallia
size: 1T
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: 17 | 17
type: statblock
weaknesses: []
---

```ds-sb
agility: 3
cost: 7 essence for two minions
ev: ""
features:
    - effects:
        - effect: Once per [turn](../../../../../rule/combat/turn.md) during their move action, each nixie under your control can [teleport](../../../../../movement/teleport.md) to a body of water within 6. The corallia can't [teleport](../../../../../movement/teleport.md) into water created by their own seafoam pool.
      feature_type: trait
      icon: ⭐️
      name: Water Weird
      type: feature
    - effects:
        - effect: The area within 2 squares of the corallia is filled with purifying saltwater that disables the effects of [difficult terrain](../../../../../movement/difficult-terrain.md) created by enemies. At the end of the corallia's [turn](../../../../../rule/combat/turn.md), the corallia can scrub you or an ally in the affected area and end one [condition](../../../../../rule/combat/condition.md).
      feature_type: trait
      icon: ⭐️
      name: Seafoam Pool
      type: feature
    - effects:
        - effect: The coralia has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: Corallias are saltwater nixies with coarse, coral-like skin and curly hair with hooked ends. Their salty tears are used to hallow places of worship and ward off demons.
free_strike: 7
immunities:
    - Lightning R
intuition: 4
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-corallia
    source: mcdm.summoner.v1
might: -2
movement: Swim
name: Nixie Corallia
organization: Minion
presence: 1
reason: 3
role: Support
size: 1T
speed: 6
stability: 0
stamina: 17 | 17
type: statblock
weaknesses: []
```
