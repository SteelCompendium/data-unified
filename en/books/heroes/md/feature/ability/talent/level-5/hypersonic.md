---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
distance: 5 x 2 line within 1
effects:
    - effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a square on the opposite side of the area before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 12 sonic damage
      tier2: 18 sonic damage
      tier3: 24 sonic damage
    - effect: If you obtain a tier 2 outcome or better, you are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) and each target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Strained
flavor: You move fast enough to [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) around and watch your foes feel the aftermath.
keywords:
    - Area
    - Charge
    - Psionic
    - Telekinesis
level: "5"
name: Hypersonic
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-5/hypersonic
target: Each enemy in the area
tier1: 12 sonic damage
tier2: 18 sonic damage
tier3: 24 sonic damage
type: ability
---


*You move fast enough to [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) around and watch your foes feel the aftermath.*

| **Area, Charge, Psionic, Telekinesis** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------|------------------------------:|
| **📏 5 x 2 line within 1**             | **🎯 Each enemy in the area** |

**Effect:** You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to a square on the opposite side of the area before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 12 sonic damage
- **12-16:** 18 sonic damage
- **17+:** 24 sonic damage

**Strained:** If you obtain a tier 2 outcome or better, you are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) and each target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
