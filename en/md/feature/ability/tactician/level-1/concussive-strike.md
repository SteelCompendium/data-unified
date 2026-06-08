---
action_type: Main action
class: tactician
cost: 3 Focus
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
flavor: Your precise strike leaves your foe struggling to respond.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Concussive Strike
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
target: One creature or object
type: ability
---


*Your precise strike leaves your foe struggling to respond.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|-----------------------------------|------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature or object** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 3 + M damage; M < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** 5 + M damage; M < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** 8 + M damage; M < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
