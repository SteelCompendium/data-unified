---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Self
effect: You jump up to your maximum jump [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space where you land.
feature_type: ability
file_basename: avalanche-impact
file_dpath: feature/ability/fury/level-6
flavor: You leap and crash down, causing a shockwave that devastates foes.
item_id: avalanche-impact
item_name: Avalanche Impact
keywords:
    - Magic
level: "6"
name: Avalanche Impact
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/avalanche-impact
source: mcdm.heroes.v1
subclass: berserker
target: Self
tier1: 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Self
effects:
    - effect: You jump up to your maximum jump [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space where you land.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: You leap and crash down, causing a shockwave that devastates foes.
keywords:
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 9 Ferocity
    distance: Self
    effect: You jump up to your maximum jump [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space where you land.
    flavor: You leap and crash down, causing a shockwave that devastates foes.
    keywords:
        - Magic
    level: "6"
    name: Avalanche Impact
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/avalanche-impact
    subclass: berserker
    target: Self
    tier1: 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Avalanche Impact
target: Self
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
