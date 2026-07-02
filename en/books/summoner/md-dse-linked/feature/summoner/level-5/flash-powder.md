---
action_type: feature
class: summoner
feature_source: circle
feature_type: feature
file_basename: flash-powder
file_dpath: feature/summoner/level-5
item_id: flash-powder
item_name: Flash Powder
level: "5"
name: Flash Powder
scc: mcdm.summoner.v1/feature.summoner.level-5/flash-powder
source: mcdm.summoner.v1
subclass: spring
type: feature
---

```ds-feature
effects:
    - effect: |-
        Each ally that gains [temporary Stamina](../../../rule/health/temporary-stamina.md) from your [Pixie Dust](../level-1/pixie-dust.md) feature also gains one of the following effects until the end of their next [turn](../../../rule/combat/turn.md) (or for 10 minutes if used outside of combat):

        - **Flight:** Their [speed](../../../rule/character/speed.md) gains the [Fly](../../../movement/fly.md) keyword.
        - **Vanish:** They become invisible.
        - **Water Weird:** As a [free maneuver](../../../rule/combat/free-maneuver.md) once per [turn](../../../rule/combat/turn.md), they can [teleport](../../../movement/teleport.md) to a body of water within 5 squares of them.
        - **Panacea:** They can end one [condition](../../../rule/combat/condition.md) affecting them or stand up.
feature_type: feature
metadata:
    class: summoner
    feature_source: circle
    level: "5"
    name: Flash Powder
    scc: mcdm.summoner.v1/feature.summoner.level-5/flash-powder
    subclass: spring
    type: feature
name: Flash Powder
type: feature
```
