---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: You can [shift](../../../../movement/shifting.md) up to 4 squares, bringing the target with you. While [grabbed](../../../../condition/grabbed.md) this way, the target takes damage equal to twice your [Might](../../../../rule/character/might.md) score at the start of each of your [turns](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: pounce
file_dpath: feature/ability/fury/level-6
flavor: You strike at the target like the ultimate predator you are.
item_id: pounce
item_name: Pounce
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "6"
name: Pounce
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
source: mcdm.heroes.v1
subclass: stormwight
target: One creature
tier1: 8 damage; M < WEAK, [grabbed](../../../../condition/grabbed.md)
tier2: 13 damage; M < AVERAGE, [grabbed](../../../../condition/grabbed.md)
tier3: 17 damage; M < STRONG, [grabbed](../../../../condition/grabbed.md)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can [shift](../../../../movement/shifting.md) up to 4 squares, bringing the target with you. While [grabbed](../../../../condition/grabbed.md) this way, the target takes damage equal to twice your [Might](../../../../rule/character/might.md) score at the start of each of your [turns](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 8 damage; M < WEAK, [grabbed](../../../../condition/grabbed.md)
      tier2: 13 damage; M < AVERAGE, [grabbed](../../../../condition/grabbed.md)
      tier3: 17 damage; M < STRONG, [grabbed](../../../../condition/grabbed.md)
feature_type: ability
flavor: You strike at the target like the ultimate predator you are.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: You can [shift](../../../../movement/shifting.md) up to 4 squares, bringing the target with you. While [grabbed](../../../../condition/grabbed.md) this way, the target takes damage equal to twice your [Might](../../../../rule/character/might.md) score at the start of each of your [turns](../../../../rule/combat/turn.md).
    flavor: You strike at the target like the ultimate predator you are.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "6"
    name: Pounce
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
    subclass: stormwight
    target: One creature
    tier1: 8 damage; M < WEAK, [grabbed](../../../../condition/grabbed.md)
    tier2: 13 damage; M < AVERAGE, [grabbed](../../../../condition/grabbed.md)
    tier3: 17 damage; M < STRONG, [grabbed](../../../../condition/grabbed.md)
    type: ability
name: Pounce
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
