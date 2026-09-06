---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
      tier2: 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
      tier3: 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area
    - effect: Targets closest to the center of the area are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) first.
      name: Effect
    - effect: The size of the area increases by 2. You also target yourself and each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
      name: Strained
flavor: You bend gravity into a fine point and pull your foes toward it.
keywords:
    - Area
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
level: "6"
name: Gravitic Well
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/gravitic-well
subclass: telekinesis
target: Each enemy and object in the area
tier1: 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
tier2: 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
tier3: 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area
type: ability
---


*You bend gravity into a fine point and pull your foes toward it.*

| **Area, Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), Telekinesis** |                             **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------|--------------------------------------------:|
| **📏 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10**                | **🎯 Each enemy and object in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
- **12-16:** 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
- **17+:** 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area

**Effect:** Targets closest to the center of the area are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) first.

**Strained:** The size of the area increases by 2. You also target yourself and each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
