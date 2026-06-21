---
action_type: Free triggered
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The effect ends on the target and is applied to the creature who imposed the effect on them. That creature also takes damage equal to three times your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
file_basename: pain-of-your-own-making
file_dpath: feature/ability/censor/level-6
flavor: You reverse the effects from an evildoer.
item_id: pain-of-your-own-making
item_name: Pain of Your Own Making
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Pain of Your Own Making
scc: mcdm.heroes.v1/feature.ability.censor.level-6/pain-of-your-own-making
source: mcdm.heroes.v1
subtype: triggered
target: Self or one ally
trigger: The target gains a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effect that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: ability
---

```ds-feature
cost: 9 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The effect ends on the target and is applied to the creature who imposed the effect on them. That creature also takes damage equal to three times your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
flavor: You reverse the effects from an evildoer.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Free triggered
    class: censor
    cost: 9 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The effect ends on the target and is applied to the creature who imposed the effect on them. That creature also takes damage equal to three times your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
    flavor: You reverse the effects from an evildoer.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Pain of Your Own Making
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/pain-of-your-own-making
    subtype: triggered
    target: Self or one ally
    trigger: The target gains a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effect that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    type: ability
name: Pain of Your Own Making
target: Self or one ally
trigger: The target gains a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or effect that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: feature
usage: Free triggered
```
