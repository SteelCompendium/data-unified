---
action_type: feature
class: summoner
feature_source: circle
feature_type: feature
file_basename: pixie-lift
file_dpath: feature/summoner/level-5
item_id: pixie-lift
item_name: Pixie Lift
level: "5"
name: Pixie Lift
scc: mcdm.summoner.v1/feature.summoner.level-5/pixie-lift
source: mcdm.summoner.v1
subclass: spring
type: feature
---

```ds-feature
effects:
    - effect: |-
        Your [speed](../../../rule/character/speed.md) gains the [Fly](../../../movement/fly.md) and [Hover](../../../movement/hover.md) keywords. You lose the [Hover](../../../movement/hover.md) keyword from this feature while you are [dazed](../../../condition/dazed.md), [dying](../../../rule/health/dying.md), or you fly more than 1 square above the surface of the ground.

        If your [speed](../../../rule/character/speed.md) previously had the [Fly](../../../movement/fly.md) keyword, you can now [fly](../../../movement/fly.md) while sneaking an additional number of squares equal to your [Reason](../../../rule/character/reason.md).
feature_type: feature
metadata:
    class: summoner
    feature_source: circle
    level: "5"
    name: Pixie Lift
    scc: mcdm.summoner.v1/feature.summoner.level-5/pixie-lift
    subclass: spring
    type: feature
name: Pixie Lift
type: feature
```
