---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 11 Drama
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
      tier3: 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
    - effect: Each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc.v1:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "8"
name: The Show Must Go On
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
target: Each enemy in the area
tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
tier3: 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
type: ability
---


*You shine a bright light on the players on the stage and compel them to finish the performance.*

| **Area, Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)** | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)**                  |
|-------------------------|-------------------------------|
| **📏 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10** | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
- **17+:** 12 damage; the target can't willingly leave the area ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)

**Effect:** Each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc.v1:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
