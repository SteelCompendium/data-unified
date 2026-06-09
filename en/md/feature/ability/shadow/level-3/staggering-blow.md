---
action_type: Main action
class: shadow
cost: 7 Insight
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
flavor: There's no recovering from this.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Staggering Blow
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
target: One creature
tier1: 7 + A damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 11 + A damage; M < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier3: 16 + A damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---


*There's no recovering from this.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 7 + A damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 11 + A damage; M < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
- **17+:** 16 + A damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
