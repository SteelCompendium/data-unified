---
action_type: Triggered
class: summoner
distance: Summoner's Range
effect: You summon a signature minion in an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to the target. If the target is [force moved](../../../../movement/forced-movement.md) into the minion, you can choose to make the target take no [damage](../../../../rule/damage/damage.md) from the collision.
feature_source: summoner
feature_type: ability
file_basename: halt
file_dpath: feature/ability/summoner/level-1
flavor: You order a minion to get in the way.
item_id: halt
item_name: Halt!
keywords: []
level: "1"
name: Halt!
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/halt
source: mcdm.summoner.v1
target: One creature
trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: You summon a signature minion in an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to the target. If the target is [force moved](../../../../movement/forced-movement.md) into the minion, you can choose to make the target take no [damage](../../../../rule/damage/damage.md) from the collision.
feature_type: ability
flavor: You order a minion to get in the way.
keywords: []
metadata:
    action_type: Triggered
    class: summoner
    distance: Summoner's Range
    effect: You summon a signature minion in an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to the target. If the target is [force moved](../../../../movement/forced-movement.md) into the minion, you can choose to make the target take no [damage](../../../../rule/damage/damage.md) from the collision.
    feature_source: summoner
    flavor: You order a minion to get in the way.
    keywords: []
    level: "1"
    name: Halt!
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/halt
    target: One creature
    trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
    type: ability
name: Halt!
target: One creature
trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
type: feature
usage: Triggered
```
