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
        Each ally that gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) from your [Pixie Dust](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/pixie-dust) feature also gains one of the following effects until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) (or for 10 minutes if used outside of combat):

        - **Flight:** Their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) gains the [Fly](scc.v1:mcdm.heroes.v1/movement/fly) keyword.
        - **Vanish:** They become invisible.
        - **Water Weird:** As a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver) once per [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a body of water within 5 squares of them.
        - **Panacea:** They can end one [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) affecting them or stand up.
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
