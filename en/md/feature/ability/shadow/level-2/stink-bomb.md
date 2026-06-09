---
action_type: Main action
class: shadow
cost: 5 Insight
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: The gas remains in the area until the end of the encounter. Any creature who starts their [turn](scc:mcdm.heroes.v1/rule.combat/turn) in the area and has M < AVERAGE is [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends).
flavor: Putrid yellow gas explodes from a bomb you toss.
keywords:
    - Area
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Stink Bomb
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/stink-bomb
target: Each creature in the area
tier1: 2 poison damage
tier2: 5 poison damage
tier3: 7 poison damage
type: ability
---


*Putrid yellow gas explodes from a bomb you toss.*

| **Area, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)**        |                  **Main action** |
|-------------------------|---------------------------------:|
| **📏 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10** | **🎯 Each creature in the area** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 2 poison damage
- **12-16:** 5 poison damage
- **17+:** 7 poison damage

**Effect:** The gas remains in the area until the end of the encounter. Any creature who starts their [turn](scc:mcdm.heroes.v1/rule.combat/turn) in the area and has M < AVERAGE is [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends).
