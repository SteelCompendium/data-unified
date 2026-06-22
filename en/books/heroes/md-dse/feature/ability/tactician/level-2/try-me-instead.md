---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Self; see below
effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 against a creature.
feature_type: ability
file_basename: try-me-instead
file_dpath: feature/ability/tactician/level-2
flavor: '"Try picking on someone my [size](scc.v1:mcdm.heroes.v1/rule.character/size)."'
item_id: try-me-instead
item_name: Try Me Instead
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Try Me Instead
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
source: mcdm.heroes.v1
subclass: insurgent
target: Self
tier1: 2 + R damage; R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 3 + R damage; R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 4 + R damage; R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 5 Focus
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 against a creature.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage; R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 3 + R damage; R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 4 + R damage; R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: '"Try picking on someone my [size](scc.v1:mcdm.heroes.v1/rule.character/size)."'
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: Self; see below
    effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 against a creature.
    flavor: '"Try picking on someone my [size](scc.v1:mcdm.heroes.v1/rule.character/size)."'
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Try Me Instead
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
    subclass: insurgent
    target: Self
    tier1: 2 + R damage; R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 3 + R damage; R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 4 + R damage; R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Try Me Instead
target: Self
type: feature
usage: Main action
```
