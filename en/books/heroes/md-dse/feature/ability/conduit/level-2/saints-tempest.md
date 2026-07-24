---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 5 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 7 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
file_basename: saints-tempest
file_dpath: feature/ability/conduit/level-2
flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
item_id: saints-tempest
item_name: Saint's Tempest
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Saint's Tempest
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/saints-tempest
source: mcdm.heroes.v1
subclass: storm
target: Each enemy in the area
tier1: 2 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 5 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 7 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 5 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 7 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 5 Piety
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 2 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 5 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 7 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Saint's Tempest
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/saints-tempest
    subclass: storm
    target: Each enemy in the area
    tier1: 2 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 5 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 7 lightning damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Saint's Tempest
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
