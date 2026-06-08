---
action_type: Main action
class: shadow
cost: 7 Insight
distance: Melee 1 or ranged 5
flavor: There's no recovering from this.
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Staggering Blow
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
target: One creature
type: ability
---


*There's no recovering from this.*

| **Melee, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 Melee 1 or ranged 5**        | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 7 + A damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 11 + A damage; M < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
- **17+:** 16 + A damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
