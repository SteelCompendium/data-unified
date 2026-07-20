---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: You can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) each willing ally in the area the same [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
feature_type: ability
file_basename: call-the-thunder-down
file_dpath: feature/ability/conduit/level-1
flavor: You ask your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) for thunder and your prayer is answered.
item_id: call-the-thunder-down
item_name: Call the Thunder Down
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Call the Thunder Down
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 5 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
cost: 3 Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: You can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) each willing ally in the area the same [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 5 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: You ask your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) for thunder and your prayer is answered.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 3 Piety
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: You can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) each willing ally in the area the same [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
    flavor: You ask your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) for thunder and your prayer is answered.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Call the Thunder Down
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
    target: Each enemy in the area
    tier1: 2 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 5 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Call the Thunder Down
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
