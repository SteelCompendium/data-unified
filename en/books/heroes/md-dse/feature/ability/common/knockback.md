---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
      tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    - effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
      name: Effect
feature_type: ability
file_basename: knockback
file_dpath: feature/ability/common
item_id: knockback
item_name: Knockback
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
name: Knockback
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.common/knockback
source: mcdm.heroes.v1
target: One creature
tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
      tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    - effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
      name: Effect
feature_type: ability
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
          tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
          tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
        - effect: You can usually target only creatures of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller. If your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score is 2 or higher, you can target any creature with a [size](scc.v1:mcdm.heroes.v1/rule.character/size) equal to or less than your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
          name: Effect
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    name: Knockback
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.common/knockback
    target: One creature
    tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
    tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
    tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    type: ability
name: Knockback
target: One creature
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
