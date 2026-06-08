---
action_type: Main action
class: troubadour
cost: 5 Drama
distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
flavor: Give the audience a surprise.
keywords:
    - Area
    - Magic
level: "1"
name: Dramatic Reversal
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/dramatic-reversal
target: Self and each ally in the area
type: ability
---


*Give the audience a surprise.*

| **Area, Magic** |                       **Main action** |
|-----------------|--------------------------------------:|
| **📏 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)**  | **🎯 Self and each ally in the area** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** The target can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square and make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike).
- **12-16:** The target can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares and make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc:mcdm.heroes.v1/rule.dice/edge).
- **17+:** The target can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 3 squares and make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) that gains an [edge](scc:mcdm.heroes.v1/rule.dice/edge), then can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
