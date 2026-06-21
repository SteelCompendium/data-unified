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
        The first time on a [turn](../../../rule/combat/turn.md) that you use your [Judgment](../../ability/censor/level-1/judgment.md) ability to judge a creature, you gain the following benefit based on your order:

        - **Exorcist:** You can [teleport](../../../movement/teleport.md) up to a number of squares equal to twice your [Presence](../../../rule/character/presence.md) score. This movement must take you closer to the judged creature. You do not need [line of effect](../../../rule/combat/line-of-effect.md) to your destination.
        - **Oracle:** You can deal holy damage equal to twice your [Presence](../../../rule/character/presence.md) score to the judged creature.
        - **Paragon:** You can vertical [pull](../../../movement/forced-movement.md) the judged creature up to a number of squares equal to twice your [Presence](../../../rule/character/presence.md) score.
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
