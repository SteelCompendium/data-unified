---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow the target to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md). The target can then take their [turn](../../../../rule/combat/turn.md) immediately before the triggering enemy.
      name: Effect
feature_type: ability
file_basename: prescient-grace
file_dpath: feature/ability/censor/level-2
flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
item_id: prescient-grace
item_name: Prescient Grace
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Prescient Grace
scc: mcdm.heroes.v1/feature.ability.censor.level-2/prescient-grace
source: mcdm.heroes.v1
subclass: oracle
subtype: triggered
target: Self or one ally
trigger: An enemy within 10 squares starts their [turn](../../../../rule/combat/turn.md).
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow the target to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md). The target can then take their [turn](../../../../rule/combat/turn.md) immediately before the triggering enemy.
      name: Effect
feature_type: ability
flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: censor
    cost: 5 Wrath
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: You can spend a [Recovery](../../../../rule/health/recoveries.md) to allow the target to regain [Stamina](../../../../rule/health/stamina.md) equal to your [recovery value](../../../../rule/health/recoveries.md). The target can then take their [turn](../../../../rule/combat/turn.md) immediately before the triggering enemy.
          name: Effect
    flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Prescient Grace
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/prescient-grace
    subclass: oracle
    subtype: triggered
    target: Self or one ally
    trigger: An enemy within 10 squares starts their [turn](../../../../rule/combat/turn.md).
    type: ability
name: Prescient Grace
target: Self or one ally
trigger: An enemy within 10 squares starts their [turn](../../../../rule/combat/turn.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
