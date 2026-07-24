---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 7 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 9 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
flavor: You contort your enemy's body into a stance they struggle to escape from.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Joint Lock
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/joint-lock
subtype: signature
target: One creature or object
tier1: 4 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 7 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 9 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---


*You contort your enemy's body into a stance they struggle to escape from.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                     | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + A damage; A < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 7 + A damage; A < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **17+:** 9 + A damage; A < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
