---
action_type: Main action
class: shadow
cost: 3 Insight
distance: Melee 1 or ranged 5
flavor: You leave your foe bleeding out after a devastating attack.
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Eviscerate
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
target: One creature
type: ability
---


*You leave your foe bleeding out after a devastating attack.*

| **Melee, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 Melee 1 or ranged 5**        | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + A damage; A < WEAK, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
- **12-16:** 6 + A damage; A < AVERAGE, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
- **17+:** 10 + A damage; A < STRONG, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
