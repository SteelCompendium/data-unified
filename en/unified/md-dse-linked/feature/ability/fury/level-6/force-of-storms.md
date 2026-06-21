---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: When the target ends this [forced movement](../../../../movement/forced-movement.md), each creature within 2 squares of the target is [pushed](../../../../movement/forced-movement.md) 3 squares.
feature_type: ability
file_basename: force-of-storms
file_dpath: feature/ability/fury/level-6
flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
item_id: force-of-storms
item_name: Force of Storms
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "6"
name: Force of Storms
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/force-of-storms
source: mcdm.heroes.v1
target: One creature
tier1: 7 + M damage; [push](../../../../movement/forced-movement.md) 3
tier2: 11 + M damage; [push](../../../../movement/forced-movement.md) 5
tier3: 16 + M damage; [push](../../../../movement/forced-movement.md) 7
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: When the target ends this [forced movement](../../../../movement/forced-movement.md), each creature within 2 squares of the target is [pushed](../../../../movement/forced-movement.md) 3 squares.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 7 + M damage; [push](../../../../movement/forced-movement.md) 3
      tier2: 11 + M damage; [push](../../../../movement/forced-movement.md) 5
      tier3: 16 + M damage; [push](../../../../movement/forced-movement.md) 7
feature_type: ability
flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: When the target ends this [forced movement](../../../../movement/forced-movement.md), each creature within 2 squares of the target is [pushed](../../../../movement/forced-movement.md) 3 squares.
    flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "6"
    name: Force of Storms
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/force-of-storms
    target: One creature
    tier1: 7 + M damage; [push](../../../../movement/forced-movement.md) 3
    tier2: 11 + M damage; [push](../../../../movement/forced-movement.md) 5
    tier3: 16 + M damage; [push](../../../../movement/forced-movement.md) 7
    type: ability
name: Force of Storms
target: One creature
type: feature
usage: Main action
```
