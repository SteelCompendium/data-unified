---
action_type: Main action
class: talent
distance: Ranged 10
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - Ranged
    - Strike
level: "1"
name: Hoarfrost
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
subtype: signature
target: One creature
type: ability
---


*You blast a foe with a pulse of cold energy.*

| **Cryokinesis, Psionic, Ranged**, **Strike** |     **Main action** |
|----------------------------------------------|--------------------:|
| **📏 Ranged 10**                             | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 2 + R cold damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 4 + R cold damage; M < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **17+:** 6 + R cold damage; M < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))

**Strained:** You are [slowed](scc:mcdm.heroes.v1/condition/slowed) until the end of your next turn. Additionally, a target [slowed](scc:mcdm.heroes.v1/condition/slowed) by this ability is [restrained](scc:mcdm.heroes.v1/condition/restrained) instead.
