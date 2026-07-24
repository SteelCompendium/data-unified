---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: censor
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
    - cost: Spend 1 Wrath
      effect: You can end one effect on the target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone](scc.v1:mcdm.heroes.v1/condition/prone) target can stand up.
feature_type: ability
file_basename: my-life-for-yours
file_dpath: feature/ability/censor/level-1
flavor: You channel some of your vitality into more resilience for you or an ally.
item_id: my-life-for-yours
item_name: My Life for Yours
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: My Life for Yours
scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
source: mcdm.heroes.v1
subtype: triggered
target: Self or one ally
trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
    - cost: Spend 1 Wrath
      effect: You can end one effect on the target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone](scc.v1:mcdm.heroes.v1/condition/prone) target can stand up.
feature_type: ability
flavor: You channel some of your vitality into more resilience for you or an ally.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: censor
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: You spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
        - cost: Spend 1 Wrath
          effect: You can end one effect on the target that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone](scc.v1:mcdm.heroes.v1/condition/prone) target can stand up.
    flavor: You channel some of your vitality into more resilience for you or an ally.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: My Life for Yours
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
    type: ability
name: My Life for Yours
target: Self or one ally
trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
