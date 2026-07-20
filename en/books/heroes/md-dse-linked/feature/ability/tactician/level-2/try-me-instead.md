---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Self; see below
effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) directly toward an ally, ending [adjacent](../../../../rule/combat/adjacent.md) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](../../../../rule/health/recoveries.md), and you can make the following weapon [strike](../../../../rule/combat/strike.md) with a [distance](../../../../rule/combat/distance.md) of [melee](../../../../rule/combat/melee.md) 1 against a creature.
feature_type: ability
file_basename: try-me-instead
file_dpath: feature/ability/tactician/level-2
flavor: '"Try picking on someone my [size](../../../../rule/character/size.md)."'
item_id: try-me-instead
item_name: Try Me Instead
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: Try Me Instead
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
source: mcdm.heroes.v1
subclass: insurgent
target: Self
tier1: 2 + R damage; R < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
tier2: 3 + R damage; R < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
tier3: 4 + R damage; R < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Focus
distance: Self; see below
effects:
    - effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) directly toward an ally, ending [adjacent](../../../../rule/combat/adjacent.md) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](../../../../rule/health/recoveries.md), and you can make the following weapon [strike](../../../../rule/combat/strike.md) with a [distance](../../../../rule/combat/distance.md) of [melee](../../../../rule/combat/melee.md) 1 against a creature.
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 + R damage; R < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 3 + R damage; R < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 4 + R damage; R < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: '"Try picking on someone my [size](../../../../rule/character/size.md)."'
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 5 Focus
    distance: Self; see below
    effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) directly toward an ally, ending [adjacent](../../../../rule/combat/adjacent.md) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](../../../../rule/health/recoveries.md), and you can make the following weapon [strike](../../../../rule/combat/strike.md) with a [distance](../../../../rule/combat/distance.md) of [melee](../../../../rule/combat/melee.md) 1 against a creature.
    flavor: '"Try picking on someone my [size](../../../../rule/character/size.md)."'
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: Try Me Instead
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
    subclass: insurgent
    target: Self
    tier1: 2 + R damage; R < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 3 + R damage; R < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 4 + R damage; R < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Try Me Instead
target: Self
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
