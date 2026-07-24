---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: "null"
cost: 11 Discipline
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
      tier2: I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
      tier3: I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
    - effect: If the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the round continues as if they had acted. A target who doesn't lose their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score for each main action they take until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Arrestor Cycle
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.null.level-9/arrestor-cycle
subclass: chronokinetic
subtype: triggered
target: One creature
tier1: I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
tier2: I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
tier3: I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
trigger: The triggering creature starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: ability
---


*You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.*

| **Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)** |  **Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
|---------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**    | **🎯 One creature** |

**Trigger:** The triggering creature starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** I < WEAK, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
- **12-16:** I < AVERAGE, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)
- **17+:** I < STRONG, the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)

**Effect:** If the target loses their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the round continues as if they had acted. A target who doesn't lose their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score for each main action they take until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
