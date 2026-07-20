---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: back
file_dpath: feature/ability/fury/level-1
flavor: You hew about you with your mighty weapon, hurling enemies backward.
item_id: back
item_name: Back!
keywords:
    - Area
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Back!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 damage
tier2: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 5 damage
      tier2: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: You hew about you with your mighty weapon, hurling enemies backward.
keywords:
    - Area
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 3 Ferocity
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: You hew about you with your mighty weapon, hurling enemies backward.
    keywords:
        - Area
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "1"
    name: Back!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
    target: Each enemy in the area
    tier1: 5 damage
    tier2: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Back!
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
