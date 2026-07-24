---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 6 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: You can choose to have this ability deal damage to and [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) objects, and to deal damage to buildings.
      name: Special
feature_type: ability
file_basename: invocation-of-undoing
file_dpath: feature/ability/conduit/level-6
flavor: You utter a secret word of destruction known only to deities.
item_id: invocation-of-undoing
item_name: Invocation of Undoing
keywords:
    - Area
    - Magic
level: "6"
name: Invocation of Undoing
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/invocation-of-undoing
source: mcdm.heroes.v1
subclass: knowledge
target: Each enemy in the area
tier1: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 6 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 6 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: You can choose to have this ability deal damage to and [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) objects, and to deal damage to buildings.
      name: Special
feature_type: ability
flavor: You utter a secret word of destruction known only to deities.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 6 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
        - effect: You can choose to have this ability deal damage to and [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) objects, and to deal damage to buildings.
          name: Special
    flavor: You utter a secret word of destruction known only to deities.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Invocation of Undoing
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/invocation-of-undoing
    subclass: knowledge
    target: Each enemy in the area
    tier1: 3 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 6 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 9 sonic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Invocation of Undoing
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
