---
action_type: Triggered
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: breath-of-dawn-remembered
file_dpath: feature/ability/elementalist/level-1
flavor: The power you channel grants the ability to get back in the fight.
item_id: breath-of-dawn-remembered
item_name: Breath of Dawn Remembered
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Breath of Dawn Remembered
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/breath-of-dawn-remembered
source: mcdm.heroes.v1
spend: '1+ Essence: The target can spend an additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) for each essence spent.'
subtype: triggered
target: Self or one ally
trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - effect: '1+ Essence: The target can spend an additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) for each essence spent.'
      name: Spend
feature_type: ability
flavor: The power you channel grants the ability to get back in the fight.
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Triggered
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: The power you channel grants the ability to get back in the fight.
    keywords:
        - Green
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Breath of Dawn Remembered
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/breath-of-dawn-remembered
    spend: '1+ Essence: The target can spend an additional [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) for each essence spent.'
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
    type: ability
name: Breath of Dawn Remembered
target: Self or one ally
trigger: The target starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) or takes damage.
type: feature
usage: Triggered
```
