---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Three 10 x 1 lines within 1
effect: The targets are [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) one at a time, starting with the target nearest to you, and can be [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into other targets in the same line.
feature_type: ability
file_basename: lightning-lord
file_dpath: feature/ability/conduit/level-6
flavor: Lightning [bursts](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from your body in several directions.
item_id: lightning-lord
item_name: Lightning Lord
keywords:
    - Area
    - Magic
level: "6"
name: Lightning Lord
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/lightning-lord
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 9 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 13 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
cost: 9 Piety
distance: Three 10 x 1 lines within 1
effects:
    - effect: The targets are [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) one at a time, starting with the target nearest to you, and can be [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into other targets in the same line.
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 6 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 9 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 13 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: Lightning [bursts](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from your body in several directions.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Three 10 x 1 lines within 1
    effect: The targets are [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) one at a time, starting with the target nearest to you, and can be [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) into other targets in the same line.
    flavor: Lightning [bursts](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from your body in several directions.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Lightning Lord
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/lightning-lord
    target: Each enemy in the area
    tier1: 6 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 9 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 13 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Lightning Lord
target: Each enemy in the area
type: feature
usage: Main action
```
