---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: nature-judges-thee
file_dpath: feature/ability/conduit/level-2
flavor: Mystical thorned vines appear at your bidding and bind your foes.
item_id: nature-judges-thee
item_name: Nature Judges Thee
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Nature Judges Thee
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
source: mcdm.heroes.v1
subclass: nature
target: Each enemy in the area
tier1: 2 damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 3 damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 7 damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 3 damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 7 damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: Mystical thorned vines appear at your bidding and bind your foes.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 5 Piety
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    flavor: Mystical thorned vines appear at your bidding and bind your foes.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Nature Judges Thee
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
    subclass: nature
    target: Each enemy in the area
    tier1: 2 damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 3 damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 7 damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Nature Judges Thee
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
