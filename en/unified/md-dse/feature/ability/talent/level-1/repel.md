---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target takes half the triggering damage, or the [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced to 0 squares, the target can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
feature_type: ability
file_basename: repel
file_dpath: feature/ability/talent/level-1
flavor: They aren't going anywhere, but you might!
item_id: repel
item_name: Repel
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Repel
scc: mcdm.heroes.v1/feature.ability.talent.level-1/repel
source: mcdm.heroes.v1
subclass: telekinesis
subtype: triggered
target: Self or one ally
trigger: The target takes damage or is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target takes half the triggering damage, or the [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced to 0 squares, the target can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
feature_type: ability
flavor: They aren't going anywhere, but you might!
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target takes half the triggering damage, or the [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of the triggering [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. If the target took damage and was force moved, you choose the effect. If the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced to 0 squares, the target can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
    flavor: They aren't going anywhere, but you might!
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Repel
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/repel
    subclass: telekinesis
    subtype: triggered
    target: Self or one ally
    trigger: The target takes damage or is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
    type: ability
name: Repel
target: Self or one ally
trigger: The target takes damage or is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
