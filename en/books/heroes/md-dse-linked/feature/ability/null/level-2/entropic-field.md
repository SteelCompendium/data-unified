---
action_type: Main action
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: 3 [cube](../../../../rule/combat/cube.md) within 1
feature_type: ability
file_basename: entropic-field
file_dpath: feature/ability/null/level-2
flavor: You drastically increase the local entropy.
item_id: entropic-field
item_name: Entropic Field
keywords:
    - Area
    - Psionic
    - Weapon
level: "2"
name: Entropic Field
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-2/entropic-field
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 cold damage; A < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 9 cold damage; A < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 13 cold damage; A < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Discipline
distance: 3 [cube](../../../../rule/combat/cube.md) within 1
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 6 cold damage; A < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 9 cold damage; A < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 13 cold damage; A < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You drastically increase the local entropy.
keywords:
    - Area
    - Psionic
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 5 Discipline
    distance: 3 [cube](../../../../rule/combat/cube.md) within 1
    flavor: You drastically increase the local entropy.
    keywords:
        - Area
        - Psionic
        - Weapon
    level: "2"
    name: Entropic Field
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-2/entropic-field
    target: Each enemy in the area
    tier1: 6 cold damage; A < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 9 cold damage; A < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 13 cold damage; A < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Entropic Field
target: Each enemy in the area
type: feature
usage: Main action
```
