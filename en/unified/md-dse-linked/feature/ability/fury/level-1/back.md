---
action_type: Main action
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: 1 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: back
file_dpath: feature/ability/fury/level-1
flavor: You hew about you with your mighty weapon, hurling enemies backward.
item_id: back
item_name: Back!
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "1"
name: Back!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 damage
tier2: 8 damage; [push](../../../../movement/forced-movement.md) 1
tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: 1 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 5 damage
      tier2: 8 damage; [push](../../../../movement/forced-movement.md) 1
      tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
feature_type: ability
flavor: You hew about you with your mighty weapon, hurling enemies backward.
keywords:
    - Area
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 3 Ferocity
    distance: 1 [burst](../../../../rule/combat/burst.md)
    flavor: You hew about you with your mighty weapon, hurling enemies backward.
    keywords:
        - Area
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "1"
    name: Back!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
    target: Each enemy in the area
    tier1: 5 damage
    tier2: 8 damage; [push](../../../../movement/forced-movement.md) 1
    tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
    type: ability
name: Back!
target: Each enemy in the area
type: feature
usage: Main action
```
