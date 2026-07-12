---
action_type: Triggered
class: summoner
distance: Summoner's Range
effect: The target gains a [surge](../../../../rule/resource/surge.md) for each of your minions [adjacent](../../../../rule/combat/adjacent.md) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
feature_source: summoner
feature_type: ability
file_basename: focus-fire
file_dpath: feature/ability/summoner/level-1
flavor: You ensure the enemy can't escape the incoming attack.
item_id: focus-fire
item_name: Focus Fire!
keywords: []
level: "1"
name: Focus Fire!
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/focus-fire
source: mcdm.summoner.v1
spend: '1 Essence: If the triggering damage is from an ability that uses a [power roll](../../../../rule/dice/power-roll.md), the [power roll](../../../../rule/dice/power-roll.md) gains an [edge](../../../../rule/dice/edge.md).'
target: Self or one ally
trigger: The target deals [damage](../../../../rule/damage/damage.md) to another creature.
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: The target gains a [surge](../../../../rule/resource/surge.md) for each of your minions [adjacent](../../../../rule/combat/adjacent.md) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
    - effect: '1 Essence: If the triggering damage is from an ability that uses a [power roll](../../../../rule/dice/power-roll.md), the [power roll](../../../../rule/dice/power-roll.md) gains an [edge](../../../../rule/dice/edge.md).'
      name: Spend
feature_type: ability
flavor: You ensure the enemy can't escape the incoming attack.
keywords: []
metadata:
    action_type: Triggered
    class: summoner
    distance: Summoner's Range
    effect: The target gains a [surge](../../../../rule/resource/surge.md) for each of your minions [adjacent](../../../../rule/combat/adjacent.md) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
    feature_source: summoner
    flavor: You ensure the enemy can't escape the incoming attack.
    keywords: []
    level: "1"
    name: Focus Fire!
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/focus-fire
    spend: '1 Essence: If the triggering damage is from an ability that uses a [power roll](../../../../rule/dice/power-roll.md), the [power roll](../../../../rule/dice/power-roll.md) gains an [edge](../../../../rule/dice/edge.md).'
    target: Self or one ally
    trigger: The target deals [damage](../../../../rule/damage/damage.md) to another creature.
    type: ability
name: Focus Fire!
target: Self or one ally
trigger: The target deals [damage](../../../../rule/damage/damage.md) to another creature.
type: feature
usage: Triggered
```
