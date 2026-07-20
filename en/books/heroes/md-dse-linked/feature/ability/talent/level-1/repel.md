---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: talent
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The target takes half the triggering damage, or the [distance](../../../../rule/combat/distance.md) of the triggering [forced movement](../../../../movement/forced-movement.md) is reduced by a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](../../../../movement/forced-movement.md) is reduced to 0 squares, the target can [push](../../../../movement/forced-movement.md) the source of the [forced movement](../../../../movement/forced-movement.md) a number of squares equal to your [Reason](../../../../rule/character/reason.md) score.
feature_type: ability
file_basename: repel
file_dpath: feature/ability/talent/level-1
flavor: They aren't going anywhere, but you might!
item_id: repel
item_name: Repel
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Repel
scc: mcdm.heroes.v1/feature.ability.talent.level-1/repel
source: mcdm.heroes.v1
subclass: telekinesis
subtype: triggered
target: Self or one ally
trigger: The target takes damage or is [force moved](../../../../movement/forced-movement.md).
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target takes half the triggering damage, or the [distance](../../../../rule/combat/distance.md) of the triggering [forced movement](../../../../movement/forced-movement.md) is reduced by a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](../../../../movement/forced-movement.md) is reduced to 0 squares, the target can [push](../../../../movement/forced-movement.md) the source of the [forced movement](../../../../movement/forced-movement.md) a number of squares equal to your [Reason](../../../../rule/character/reason.md) score.
feature_type: ability
flavor: They aren't going anywhere, but you might!
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: talent
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The target takes half the triggering damage, or the [distance](../../../../rule/combat/distance.md) of the triggering [forced movement](../../../../movement/forced-movement.md) is reduced by a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](../../../../movement/forced-movement.md) is reduced to 0 squares, the target can [push](../../../../movement/forced-movement.md) the source of the [forced movement](../../../../movement/forced-movement.md) a number of squares equal to your [Reason](../../../../rule/character/reason.md) score.
    flavor: They aren't going anywhere, but you might!
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Repel
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/repel
    subclass: telekinesis
    subtype: triggered
    target: Self or one ally
    trigger: The target takes damage or is [force moved](../../../../movement/forced-movement.md).
    type: ability
name: Repel
target: Self or one ally
trigger: The target takes damage or is [force moved](../../../../movement/forced-movement.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
