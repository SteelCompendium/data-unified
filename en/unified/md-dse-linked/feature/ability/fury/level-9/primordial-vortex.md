---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
feature_type: ability
file_basename: primordial-vortex
file_dpath: feature/ability/fury/level-9
flavor: You channel the power of the Primordial Chaos to pull foes to you.
item_id: primordial-vortex
item_name: Primordial Vortex
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "9"
name: Primordial Vortex
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-vortex
source: mcdm.heroes.v1
subclass: berserker
target: Each enemy in the area
tier1: 3 damage; vertical [pull](../../../../movement/forced-movement.md) 3
tier2: 5 damage; vertical [pull](../../../../movement/forced-movement.md) 5
tier3: 8 damage; vertical [pull](../../../../movement/forced-movement.md) 7
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 damage; vertical [pull](../../../../movement/forced-movement.md) 3
      tier2: 5 damage; vertical [pull](../../../../movement/forced-movement.md) 5
      tier3: 8 damage; vertical [pull](../../../../movement/forced-movement.md) 7
feature_type: ability
flavor: You channel the power of the Primordial Chaos to pull foes to you.
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
    effect: If this [forced movement](../../../../movement/forced-movement.md) causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.
    flavor: You channel the power of the Primordial Chaos to pull foes to you.
    keywords:
        - Area
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "9"
    name: Primordial Vortex
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-vortex
    subclass: berserker
    target: Each enemy in the area
    tier1: 3 damage; vertical [pull](../../../../movement/forced-movement.md) 3
    tier2: 5 damage; vertical [pull](../../../../movement/forced-movement.md) 5
    tier3: 8 damage; vertical [pull](../../../../movement/forced-movement.md) 7
    type: ability
name: Primordial Vortex
target: Each enemy in the area
type: feature
usage: Main action
```
