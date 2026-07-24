---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 4 fire damage
      tier2: 6 fire damage
      tier3: 10 fire damage
    - effect: Each ally in the area deals fire damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score with their next strike made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: Light shines at your command, burning your foes and blessing your allies.
keywords:
    - Area
    - Magic
level: "2"
name: Morning Light
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/morning-light
subclass: sun
target: Each enemy in the area
tier1: 4 fire damage
tier2: 6 fire damage
tier3: 10 fire damage
type: ability
---


*Light shines at your command, burning your foes and blessing your allies.*

| **Area, Magic**  |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------|------------------------------:|
| **📏 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**   | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 4 fire damage
- **12-16:** 6 fire damage
- **17+:** 10 fire damage

**Effect:** Each ally in the area deals fire damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score with their next strike made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
