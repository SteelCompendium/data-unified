---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
distance: Self
effects:
    - effect: You jump up to your maximum jump [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space where you land.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
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
---


*You leap and crash down, causing a shockwave that devastates foes.*

| **Magic**   | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-------------|-------------:|
| **📏 Self** |  **🎯 Self** |

**Effect:** You jump up to your maximum jump [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the space where you land.

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **12-16:** 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
- **17+:** 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
