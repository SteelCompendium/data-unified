---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: You start crying, and you can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or make [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Strained
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "2"
name: Overwhelm
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
subclass: telepathy
target: One creature
tier1: 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---


*You overload their senses, turning all their subconscious thoughts into conscious ones.*

| **Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Telepathy** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                       | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

**Strained:** You start crying, and you can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or make [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
