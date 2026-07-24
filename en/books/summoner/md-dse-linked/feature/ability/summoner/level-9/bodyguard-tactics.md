---
action_type: Main action
class: summoner
distance: 5 burst
effects:
    - effect: Until the end of the encounter or you are [dying](../../../../rule/health/dying.md), each target has [damage immunity](../../../../rule/damage/damage-immunity.md) 5 and can use a [free triggered action](../../../../rule/combat/triggered-action.md) once per [turn](../../../../rule/combat/turn.md) whenever they are [force moved](../../../../movement/forced-movement.md) to reduce the distance by half.
      name: Effect
feature_source: summoner
feature_type: ability
file_basename: bodyguard-tactics
file_dpath: feature/ability/summoner/level-9
flavor: You surround your allies with a nigh-endless supply of summons that stand in the way of all impacts.
item_id: bodyguard-tactics
item_name: Bodyguard Tactics
keywords:
    - Area
    - Magic
level: "9"
name: Bodyguard Tactics
scc: mcdm.summoner.v1/feature.ability.summoner.level-9/bodyguard-tactics
source: mcdm.summoner.v1
target: Self and each non-minion ally in the area
type: ability
---

```ds-feature
distance: 5 burst
effects:
    - effect: Until the end of the encounter or you are [dying](../../../../rule/health/dying.md), each target has [damage immunity](../../../../rule/damage/damage-immunity.md) 5 and can use a [free triggered action](../../../../rule/combat/triggered-action.md) once per [turn](../../../../rule/combat/turn.md) whenever they are [force moved](../../../../movement/forced-movement.md) to reduce the distance by half.
      name: Effect
feature_type: ability
flavor: You surround your allies with a nigh-endless supply of summons that stand in the way of all impacts.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: summoner
    distance: 5 burst
    effects:
        - effect: Until the end of the encounter or you are [dying](../../../../rule/health/dying.md), each target has [damage immunity](../../../../rule/damage/damage-immunity.md) 5 and can use a [free triggered action](../../../../rule/combat/triggered-action.md) once per [turn](../../../../rule/combat/turn.md) whenever they are [force moved](../../../../movement/forced-movement.md) to reduce the distance by half.
          name: Effect
    feature_source: summoner
    flavor: You surround your allies with a nigh-endless supply of summons that stand in the way of all impacts.
    keywords:
        - Area
        - Magic
    level: "9"
    name: Bodyguard Tactics
    scc: mcdm.summoner.v1/feature.ability.summoner.level-9/bodyguard-tactics
    target: Self and each non-minion ally in the area
    type: ability
name: Bodyguard Tactics
target: Self and each non-minion ally in the area
type: feature
usage: Main action
```
