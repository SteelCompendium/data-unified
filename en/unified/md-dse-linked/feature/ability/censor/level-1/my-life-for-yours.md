---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: censor
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: You spend a [Recovery](../../../../rule/health/recoveries.md) and the target regains [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: my-life-for-yours
file_dpath: feature/ability/censor/level-1
flavor: You channel some of your vitality into more resilience for you or an ally.
item_id: my-life-for-yours
item_name: My Life for Yours
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: My Life for Yours
scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
source: mcdm.heroes.v1
spend: '1 Wrath: You can end one effect on the target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md), or a [prone](../../../../condition/prone.md) target can stand up.'
subtype: triggered
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You spend a [Recovery](../../../../rule/health/recoveries.md) and the target regains [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
    - effect: '1 Wrath: You can end one effect on the target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md), or a [prone](../../../../condition/prone.md) target can stand up.'
      name: Spend
feature_type: ability
flavor: You channel some of your vitality into more resilience for you or an ally.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: censor
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: You spend a [Recovery](../../../../rule/health/recoveries.md) and the target regains [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md).
    flavor: You channel some of your vitality into more resilience for you or an ally.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: My Life for Yours
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
    spend: '1 Wrath: You can end one effect on the target that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md), or a [prone](../../../../condition/prone.md) target can stand up.'
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
    type: ability
name: My Life for Yours
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
