---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: 5 x 1 line within 5
feature_type: ability
file_basename: they-always-line-up
file_dpath: feature/ability/shadow/level-8
flavor: You fire a projectile so fast that it passes through a line of foes, hamstringing them.
item_id: they-always-line-up
item_name: They Always Line Up
keywords:
    - Area
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Weapon
level: "8"
name: They Always Line Up
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-8/they-always-line-up
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 12 damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 18 damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 24 damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 11 Insight
distance: 5 x 1 line within 5
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 12 damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 18 damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 24 damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You fire a projectile so fast that it passes through a line of foes, hamstringing them.
keywords:
    - Area
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: 5 x 1 line within 5
    flavor: You fire a projectile so fast that it passes through a line of foes, hamstringing them.
    keywords:
        - Area
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Weapon
    level: "8"
    name: They Always Line Up
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-8/they-always-line-up
    target: Each enemy in the area
    tier1: 12 damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 18 damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 24 damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: They Always Line Up
target: Each enemy in the area
type: feature
usage: Main action
```
