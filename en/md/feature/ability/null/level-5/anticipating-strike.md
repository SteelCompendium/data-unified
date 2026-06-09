---
action_type: Free triggered
class: "null"
cost: 9 Discipline
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effect: This [strike](scc:mcdm.heroes.v1/rule.combat/strike) resolves before the triggering movement or main action.
flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Anticipating Strike
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/anticipating-strike
subtype: triggered
target: One creature
tier1: 7 + A damage; I < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 10 + A damage; I < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 13 + A damage; I < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
trigger: The target moves or uses a main action.
type: ability
---


*You suddenly strike an enemy, then grab them in a psionically enhanced grip.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |  **Free triggered** |
|------------------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**                     | **🎯 One creature** |

**Trigger:** The target moves or uses a main action.

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 7 + A damage; I < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
- **12-16:** 10 + A damage; I < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
- **17+:** 13 + A damage; I < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** This [strike](scc:mcdm.heroes.v1/rule.combat/strike) resolves before the triggering movement or main action.
