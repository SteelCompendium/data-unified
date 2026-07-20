---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: elementalist
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: breath-of-dawn-remembered
file_dpath: feature/ability/elementalist/level-1
flavor: The power you channel grants the ability to get back in the fight.
item_id: breath-of-dawn-remembered
item_name: Breath of Dawn Remembered
keywords:
    - Green
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Breath of Dawn Remembered
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/breath-of-dawn-remembered
source: mcdm.heroes.v1
spend: '1+ Essence: The target can spend an additional [Recovery](../../../../rule/health/recoveries.md) for each essence spent.'
subclass: green
subtype: triggered
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
    - effect: '1+ Essence: The target can spend an additional [Recovery](../../../../rule/health/recoveries.md) for each essence spent.'
      name: Spend
feature_type: ability
flavor: The power you channel grants the ability to get back in the fight.
keywords:
    - Green
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: elementalist
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The target can spend a [Recovery](../../../../rule/health/recoveries.md).
    flavor: The power you channel grants the ability to get back in the fight.
    keywords:
        - Green
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Breath of Dawn Remembered
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/breath-of-dawn-remembered
    spend: '1+ Essence: The target can spend an additional [Recovery](../../../../rule/health/recoveries.md) for each essence spent.'
    subclass: green
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
    type: ability
name: Breath of Dawn Remembered
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md) or takes damage.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
