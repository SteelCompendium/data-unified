---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: Special
effect: Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) to determine the area of this ability. Each target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 squares. You can target only objects of [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1L or smaller.
feature_type: ability
file_basename: fulcrum
file_dpath: feature/ability/talent/level-9
flavor: You precisely manipulate the creatures around you.
item_id: fulcrum
item_name: Fulcrum
keywords:
    - Area
    - Psionic
    - Telekinesis
level: "9"
name: Fulcrum
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-9/fulcrum
source: mcdm.heroes.v1
subclass: telekinesis
target: Each enemy and object in the area
tier1: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
tier2: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
tier3: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: Special
effects:
    - effect: Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) to determine the area of this ability. Each target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 squares. You can target only objects of [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1L or smaller.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
      tier2: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
      tier3: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
flavor: You precisely manipulate the creatures around you.
keywords:
    - Area
    - Psionic
    - Telekinesis
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 11 Clarity
    distance: Special
    effect: Make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) to determine the area of this ability. Each target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 squares. You can target only objects of [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1L or smaller.
    flavor: You precisely manipulate the creatures around you.
    keywords:
        - Area
        - Psionic
        - Telekinesis
    level: "9"
    name: Fulcrum
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-9/fulcrum
    subclass: telekinesis
    target: Each enemy and object in the area
    tier1: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    tier2: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    tier3: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    type: ability
name: Fulcrum
target: Each enemy and object in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
