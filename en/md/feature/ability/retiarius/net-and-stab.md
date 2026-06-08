---
action_type: Main action
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: retiarius
name: Net and Stab
scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
subtype: signature
target: One creature
type: ability
---

*The well-thrown net that follows your main attack leaves your foes right where you want them.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 6 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **17+:** 8 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
