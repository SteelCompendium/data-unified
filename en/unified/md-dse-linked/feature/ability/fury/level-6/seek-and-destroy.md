---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md).
feature_type: ability
file_basename: seek-and-destroy
file_dpath: feature/ability/fury/level-6
flavor: You break through the enemy lines to make an example.
item_id: seek-and-destroy
item_name: Seek and Destroy
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "6"
name: Seek and Destroy
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
source: mcdm.heroes.v1
subclass: reaver
target: One creature
tier1: 4 + M damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
tier2: 6 + M damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
tier3: 10 + M damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 + M damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 6 + M damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 10 + M damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: You break through the enemy lines to make an example.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md).
    flavor: You break through the enemy lines to make an example.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "6"
    name: Seek and Destroy
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
    subclass: reaver
    target: One creature
    tier1: 4 + M damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 6 + M damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 10 + M damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Seek and Destroy
target: One creature
type: feature
usage: Main action
```
