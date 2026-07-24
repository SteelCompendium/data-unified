---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 11 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 8 + I cold damage; M < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 11 + I cold damage; M < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 15 + I cold damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, the target takes cold damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn). Additionally, whenever the target damages another creature while [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) associated with the damage is reduced by 2.
      name: Effect
flavor: You drain all the heat from the target.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "9"
name: Heat Drain
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.null.level-9/heat-drain
subclass: cryokinetic
target: One creature
tier1: 8 + I cold damage; M < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 11 + I cold damage; M < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 15 + I cold damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---


*You drain all the heat from the target.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)** |        **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**             | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 8 + I cold damage; M < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
- **12-16:** 11 + I cold damage; M < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
- **17+:** 15 + I cold damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, the target takes cold damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn). Additionally, whenever the target damages another creature while [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) associated with the damage is reduced by 2.
