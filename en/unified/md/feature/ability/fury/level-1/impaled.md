---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
flavor: You skewer your enemy like a boar upon a spit.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Impaled!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
subtype: signature
target: One creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller
tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---


*You skewer your enemy like a boar upon a spit.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |                             **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **17+:** 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
