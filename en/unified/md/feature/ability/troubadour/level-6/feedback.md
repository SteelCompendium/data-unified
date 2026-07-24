---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 9 Drama
distance: Three 3 [cubes](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - effect: A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) ignores this ability.
      name: Effect
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
flavor: Your music pounds the crowd to the beat until their hearts can't stand it anymore.
keywords:
    - Area
    - Magic
level: "6"
name: Feedback
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/feedback
subclass: virtuoso
target: Each enemy in the area
tier1: 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---


*Your music pounds the crowd to the beat until their hearts can't stand it anymore.*

| **Area, Magic**               |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-------------------------------|------------------------------:|
| **📏 Three 3 [cubes](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1** | **🎯 Each enemy in the area** |

**Effect:** A [prone target](scc.v1:mcdm.heroes.v1/condition/prone) ignores this ability.

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 7 sonic damage; P < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
- **12-16:** 10 sonic damage; P < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
- **17+:** 13 sonic damage; P < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
