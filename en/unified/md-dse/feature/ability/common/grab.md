---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
feature_type: ability
file_basename: grab
file_dpath: feature/ability/common
item_id: grab
item_name: Grab
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
name: Grab
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.common/grab
source: mcdm.heroes.v1
target: One creature
tier1: No effect.
tier2: You can grab the target, but if you do, the target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
tier3: The target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by you.
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: No effect.
      tier2: You can grab the target, but if you do, the target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
      tier3: The target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by you.
feature_type: ability
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    name: Grab
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.common/grab
    target: One creature
    tier1: No effect.
    tier2: You can grab the target, but if you do, the target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
    tier3: The target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by you.
    type: ability
name: Grab
target: One creature
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
