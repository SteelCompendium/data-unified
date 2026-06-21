---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to be hurled through an object, that target takes an extra 10 damage.
feature_type: ability
file_basename: death-comes-for-you-all
file_dpath: feature/ability/fury/level-9
flavor: You use your weapon to create a destructive shockwave.
item_id: death-comes-for-you-all
item_name: Death Comes for You All!
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "9"
name: Death Comes for You All!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-comes-for-you-all
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 7 damage; [push](../../../../movement/forced-movement.md) 3
tier2: 10 damage; [push](../../../../movement/forced-movement.md) 5
tier3: 15 damage; [push](../../../../movement/forced-movement.md) 7
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to be hurled through an object, that target takes an extra 10 damage.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 7 damage; [push](../../../../movement/forced-movement.md) 3
      tier2: 10 damage; [push](../../../../movement/forced-movement.md) 5
      tier3: 15 damage; [push](../../../../movement/forced-movement.md) 7
feature_type: ability
flavor: You use your weapon to create a destructive shockwave.
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to be hurled through an object, that target takes an extra 10 damage.
    flavor: You use your weapon to create a destructive shockwave.
    keywords:
        - Area
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "9"
    name: Death Comes for You All!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-comes-for-you-all
    target: Each enemy in the area
    tier1: 7 damage; [push](../../../../movement/forced-movement.md) 3
    tier2: 10 damage; [push](../../../../movement/forced-movement.md) 5
    tier3: 15 damage; [push](../../../../movement/forced-movement.md) 7
    type: ability
name: Death Comes for You All!
target: Each enemy in the area
type: feature
usage: Main action
```
