---
action_type: feature
class: censor
feature_type: feature
file_basename: judgment-order-benefit
file_dpath: feature/censor/level-1
item_id: judgment-order-benefit
item_name: Judgment Order Benefit
level: "1"
name: Judgment Order Benefit
scc: mcdm.heroes.v1/feature.censor.level-1/judgment-order-benefit
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that you use your [Judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment) ability to judge a creature, you gain the following benefit based on your order:

        - **Exorcist:** You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to a number of squares equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score. This movement must take you closer to the judged creature. You do not need [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) to your destination.
        - **Oracle:** You can deal holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to the judged creature.
        - **Paragon:** You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the judged creature up to a number of squares equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
feature_type: feature
metadata:
    class: censor
    level: "1"
    name: Judgment Order Benefit
    scc: mcdm.heroes.v1/feature.censor.level-1/judgment-order-benefit
    type: feature
name: Judgment Order Benefit
type: feature
```
