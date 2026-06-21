---
action_type: Main action
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: You can vertical [pull](../../../../movement/forced-movement.md) the target up to 2 squares. If the target is made [restrained](../../../../condition/restrained.md) by this ability, this [forced movement](../../../../movement/forced-movement.md) ignores their [stability](../../../../rule/character/stability.md).
feature_type: ability
file_basename: choke
file_dpath: feature/ability/talent/level-1
flavor: You crush a foe in a telekinetic grip.
item_id: choke
item_name: Choke
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
    - Telekinesis
level: "1"
name: Choke
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/choke
source: mcdm.heroes.v1
target: One creature
tier1: 3 + R damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 5 + R damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 8 + R damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You can vertical [pull](../../../../movement/forced-movement.md) the target up to 2 squares. If the target is made [restrained](../../../../condition/restrained.md) by this ability, this [forced movement](../../../../movement/forced-movement.md) ignores their [stability](../../../../rule/character/stability.md).
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 3 + R damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 5 + R damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 8 + R damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: You crush a foe in a telekinetic grip.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 3 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: You can vertical [pull](../../../../movement/forced-movement.md) the target up to 2 squares. If the target is made [restrained](../../../../condition/restrained.md) by this ability, this [forced movement](../../../../movement/forced-movement.md) ignores their [stability](../../../../rule/character/stability.md).
    flavor: You crush a foe in a telekinetic grip.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
        - Telekinesis
    level: "1"
    name: Choke
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/choke
    target: One creature
    tier1: 3 + R damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 5 + R damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 8 + R damage; M < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Choke
target: One creature
type: feature
usage: Main action
```
