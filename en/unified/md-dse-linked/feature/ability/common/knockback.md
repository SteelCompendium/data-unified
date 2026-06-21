---
action_type: Maneuver
distance: '[Melee](../../../rule/combat/melee.md) 1'
effect: You can usually target only creatures of your [size](../../../rule/character/size.md) or smaller. If your [Might](../../../rule/character/might.md) score is 2 or higher, you can target any creature with a [size](../../../rule/character/size.md) equal to or less than your [Might](../../../rule/character/might.md) score.
feature_type: ability
file_basename: knockback
file_dpath: feature/ability/common
item_id: knockback
item_name: Knockback
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - Weapon
name: Knockback
power_roll_characteristic: '[Might](../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.common/knockback
source: mcdm.heroes.v1
target: One creature
tier1: '[Push](../../../movement/forced-movement.md) 1'
tier2: '[Push](../../../movement/forced-movement.md) 2'
tier3: '[Push](../../../movement/forced-movement.md) 3'
type: ability
---

```ds-feature
distance: '[Melee](../../../rule/combat/melee.md) 1'
effects:
    - effect: You can usually target only creatures of your [size](../../../rule/character/size.md) or smaller. If your [Might](../../../rule/character/might.md) score is 2 or higher, you can target any creature with a [size](../../../rule/character/size.md) equal to or less than your [Might](../../../rule/character/might.md) score.
    - roll: Power Roll + [Might](../../../rule/character/might.md)
      tier1: '[Push](../../../movement/forced-movement.md) 1'
      tier2: '[Push](../../../movement/forced-movement.md) 2'
      tier3: '[Push](../../../movement/forced-movement.md) 3'
feature_type: ability
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Maneuver
    distance: '[Melee](../../../rule/combat/melee.md) 1'
    effect: You can usually target only creatures of your [size](../../../rule/character/size.md) or smaller. If your [Might](../../../rule/character/might.md) score is 2 or higher, you can target any creature with a [size](../../../rule/character/size.md) equal to or less than your [Might](../../../rule/character/might.md) score.
    keywords:
        - '[Melee](../../../rule/combat/melee.md)'
        - Weapon
    name: Knockback
    power_roll_characteristic: '[Might](../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.common/knockback
    target: One creature
    tier1: '[Push](../../../movement/forced-movement.md) 1'
    tier2: '[Push](../../../movement/forced-movement.md) 2'
    tier3: '[Push](../../../movement/forced-movement.md) 3'
    type: ability
name: Knockback
target: One creature
type: feature
usage: Maneuver
```
