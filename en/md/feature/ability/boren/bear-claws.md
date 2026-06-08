---
action_type: Main action
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
flavor: Attacks with your sharp and deadly claws grab the weak.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: boren
name: Bear Claws
scc: mcdm.heroes.v1/feature.ability.boren/bear-claws
subtype: signature
target: One creature or object
type: ability
---

*Attacks with your sharp and deadly claws grab the weak.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
- **17+:** 11 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
