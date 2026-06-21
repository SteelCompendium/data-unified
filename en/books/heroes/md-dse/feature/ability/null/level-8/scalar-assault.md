---
action_type: Main action
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
feature_type: ability
file_basename: scalar-assault
file_dpath: feature/ability/null/level-8
flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
item_id: scalar-assault
item_name: Scalar Assault
keywords:
    - Area
    - Psionic
level: "8"
name: Scalar Assault
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-8/scalar-assault
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 12 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 17 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 23 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 11 Discipline
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 12 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 17 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 23 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
feature_type: ability
flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
keywords:
    - Area
    - Psionic
metadata:
    action_type: Main action
    class: "null"
    cost: 11 Discipline
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
    flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
    keywords:
        - Area
        - Psionic
    level: "8"
    name: Scalar Assault
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-8/scalar-assault
    target: Each enemy in the area
    tier1: 12 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 17 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 23 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Scalar Assault
target: Each enemy in the area
type: feature
usage: Main action
```
