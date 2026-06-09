---
action_type: Maneuver
class: troubadour
cost: 11 Drama
distance: 5 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: Each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
keywords:
    - Area
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "8"
name: The Show Must Go On
power_roll_characteristic: '[Presence](scc:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
target: Each enemy in the area
tier1: 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
tier3: 12 damage; the target can't willingly leave the area ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)
type: ability
---


*You shine a bright light on the players on the stage and compel them to finish the performance.*

| **Area, Magic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)** | **Maneuver**                  |
|-------------------------|-------------------------------|
| **📏 5 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10** | **🎯 Each enemy in the area** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 6 damage; P < WEAK, the target can't willingly leave the area ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
- **17+:** 12 damage; the target can't willingly leave the area ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)); if P < STRONG, they can't willingly leave the area (save ends)

**Effect:** Each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc:mcdm.heroes.v1/rule.test/test) they make before the start of your next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
