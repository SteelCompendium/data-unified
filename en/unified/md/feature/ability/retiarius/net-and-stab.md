---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: retiarius
name: Net and Stab
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
subtype: signature
target: One creature
tier1: 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier3: 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
type: ability
---

*The well-thrown net that follows your main attack leaves your foes right where you want them.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 6 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
- **17+:** 8 + M or A damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
