---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: When a target would end this [forced movement](../../../../movement/forced-movement.md) by colliding with a creature or object, they take damage as usual, then are [pushed](../../../../movement/forced-movement.md) the remaining [distance](../../../../rule/combat/distance.md) away from the creature or object in the direction they came from. As long as [forced movement](../../../../movement/forced-movement.md) remains, this effect continues if the target collides with another creature or object.
feature_type: ability
file_basename: rebounding-storm
file_dpath: feature/ability/fury/level-5
flavor: You knock around enemies like playthings.
item_id: rebounding-storm
item_name: Rebounding Storm
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Rebounding Storm
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/rebounding-storm
source: mcdm.heroes.v1
target: Two creatures or objects
tier1: 9 damage; [push](../../../../movement/forced-movement.md) 3
tier2: 14 damage; [push](../../../../movement/forced-movement.md) 5
tier3: 19 damage; [push](../../../../movement/forced-movement.md) 7
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: When a target would end this [forced movement](../../../../movement/forced-movement.md) by colliding with a creature or object, they take damage as usual, then are [pushed](../../../../movement/forced-movement.md) the remaining [distance](../../../../rule/combat/distance.md) away from the creature or object in the direction they came from. As long as [forced movement](../../../../movement/forced-movement.md) remains, this effect continues if the target collides with another creature or object.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 damage; [push](../../../../movement/forced-movement.md) 3
      tier2: 14 damage; [push](../../../../movement/forced-movement.md) 5
      tier3: 19 damage; [push](../../../../movement/forced-movement.md) 7
feature_type: ability
flavor: You knock around enemies like playthings.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: When a target would end this [forced movement](../../../../movement/forced-movement.md) by colliding with a creature or object, they take damage as usual, then are [pushed](../../../../movement/forced-movement.md) the remaining [distance](../../../../rule/combat/distance.md) away from the creature or object in the direction they came from. As long as [forced movement](../../../../movement/forced-movement.md) remains, this effect continues if the target collides with another creature or object.
    flavor: You knock around enemies like playthings.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Rebounding Storm
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/rebounding-storm
    target: Two creatures or objects
    tier1: 9 damage; [push](../../../../movement/forced-movement.md) 3
    tier2: 14 damage; [push](../../../../movement/forced-movement.md) 5
    tier3: 19 damage; [push](../../../../movement/forced-movement.md) 7
    type: ability
name: Rebounding Storm
target: Two creatures or objects
type: feature
usage: Main action
```
