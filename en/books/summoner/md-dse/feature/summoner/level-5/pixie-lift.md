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
        Your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) gains the [Fly](scc.v1:mcdm.heroes.v1/movement/fly) and [Hover](scc.v1:mcdm.heroes.v1/movement/hover) keywords. You lose the [Hover](scc.v1:mcdm.heroes.v1/movement/hover) keyword from this feature while you are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or you fly more than 1 square above the surface of the ground.

        If your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) previously had the [Fly](scc.v1:mcdm.heroes.v1/movement/fly) keyword, you can now [fly](scc.v1:mcdm.heroes.v1/movement/fly) while sneaking an additional number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason).
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
