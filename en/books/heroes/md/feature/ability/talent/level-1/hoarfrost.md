---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    - effect: You are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Additionally, a target [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by this ability is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) instead.
      name: Strained
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
level: "1"
name: Hoarfrost
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
subtype: signature
target: One creature
tier1: 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier3: 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
type: ability
---


*You blast a foe with a pulse of cold energy.*

| **Cryokinesis, Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)**, **Strike** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                             | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
- **17+:** 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))

**Strained:** You are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Additionally, a target [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by this ability is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) instead.
