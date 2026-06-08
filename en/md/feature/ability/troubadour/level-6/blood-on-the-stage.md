---
action_type: Main action
class: troubadour
cost: 9 Drama
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
flavor: It's love and blood or drama and blood. Either way, there's always blood.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Blood on the Stage
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
target: One creature or object
type: ability
---


*It's love and blood or drama and blood. Either way, there's always blood.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 12 + A damage; M < WEAK, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
- **12-16:** 18 + A damage; M < AVERAGE, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
- **17+:** 24 + A damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), or if M < STRONG, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
