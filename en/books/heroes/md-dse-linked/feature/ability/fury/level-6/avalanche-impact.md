---
action_type: Maneuver
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Self
effect: You jump up to your maximum jump [distance](../../../../rule/combat/distance.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets each creature [adjacent](../../../../rule/combat/adjacent.md) to the space where you land.
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
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/avalanche-impact
source: mcdm.heroes.v1
target: Self
tier1: 4 damage; [push](../../../../movement/forced-movement.md) 1
tier2: 7 damage; [push](../../../../movement/forced-movement.md) 2
tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Self
effects:
    - effect: You jump up to your maximum jump [distance](../../../../rule/combat/distance.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets each creature [adjacent](../../../../rule/combat/adjacent.md) to the space where you land.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 damage; [push](../../../../movement/forced-movement.md) 1
      tier2: 7 damage; [push](../../../../movement/forced-movement.md) 2
      tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
feature_type: ability
flavor: You leap and crash down, causing a shockwave that devastates foes.
keywords:
    - Magic
metadata:
    action_type: Maneuver
    class: fury
    cost: 9 Ferocity
    distance: Self
    effect: You jump up to your maximum jump [distance](../../../../rule/combat/distance.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets each creature [adjacent](../../../../rule/combat/adjacent.md) to the space where you land.
    flavor: You leap and crash down, causing a shockwave that devastates foes.
    keywords:
        - Magic
    level: "6"
    name: Avalanche Impact
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/avalanche-impact
    target: Self
    tier1: 4 damage; [push](../../../../movement/forced-movement.md) 1
    tier2: 7 damage; [push](../../../../movement/forced-movement.md) 2
    tier3: 11 damage; [push](../../../../movement/forced-movement.md) 3
    type: ability
name: Avalanche Impact
target: Self
type: feature
usage: Maneuver
```
