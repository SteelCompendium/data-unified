---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: nature-judges-thee
file_dpath: feature/ability/conduit/level-2
flavor: Mystical thorned vines appear at your bidding and bind your foes.
item_id: nature-judges-thee
item_name: Nature Judges Thee
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Nature Judges Thee
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
source: mcdm.heroes.v1
subclass: nature
target: Each enemy in the area
tier1: 2 damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 3 damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 7 damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 3 damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 7 damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: Mystical thorned vines appear at your bidding and bind your foes.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 5 Piety
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: Mystical thorned vines appear at your bidding and bind your foes.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Nature Judges Thee
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
    subclass: nature
    target: Each enemy in the area
    tier1: 2 damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 3 damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 7 damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Nature Judges Thee
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
