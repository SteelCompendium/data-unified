---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effect: You can [push](../../../../movement/forced-movement.md) each willing ally in the area the same [distance](../../../../rule/combat/distance.md), ignoring [stability](../../../../rule/character/stability.md).
feature_type: ability
file_basename: call-the-thunder-down
file_dpath: feature/ability/conduit/level-1
flavor: You ask your [saint](../../../../rule/world/saint.md) for thunder and your prayer is answered.
item_id: call-the-thunder-down
item_name: Call the Thunder Down
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Call the Thunder Down
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 sonic damage; [push](../../../../movement/forced-movement.md) 1
tier2: 3 sonic damage; [push](../../../../movement/forced-movement.md) 2
tier3: 5 sonic damage; [push](../../../../movement/forced-movement.md) 3
type: ability
---

```ds-feature
cost: 3 Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: You can [push](../../../../movement/forced-movement.md) each willing ally in the area the same [distance](../../../../rule/combat/distance.md), ignoring [stability](../../../../rule/character/stability.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 sonic damage; [push](../../../../movement/forced-movement.md) 1
      tier2: 3 sonic damage; [push](../../../../movement/forced-movement.md) 2
      tier3: 5 sonic damage; [push](../../../../movement/forced-movement.md) 3
feature_type: ability
flavor: You ask your [saint](../../../../rule/world/saint.md) for thunder and your prayer is answered.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 3 Piety
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effect: You can [push](../../../../movement/forced-movement.md) each willing ally in the area the same [distance](../../../../rule/combat/distance.md), ignoring [stability](../../../../rule/character/stability.md).
    flavor: You ask your [saint](../../../../rule/world/saint.md) for thunder and your prayer is answered.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Call the Thunder Down
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
    target: Each enemy in the area
    tier1: 2 sonic damage; [push](../../../../movement/forced-movement.md) 1
    tier2: 3 sonic damage; [push](../../../../movement/forced-movement.md) 2
    tier3: 5 sonic damage; [push](../../../../movement/forced-movement.md) 3
    type: ability
name: Call the Thunder Down
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
