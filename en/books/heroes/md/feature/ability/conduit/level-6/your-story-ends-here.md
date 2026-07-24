---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 9 + I corruption damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 14 + I corruption damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 19 + I corruption damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: If this damage kills the target, you and each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
flavor: You bend the fate of a foe, willing them to die.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "6"
name: Your Story Ends Here
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
subclass: fate
target: One creature
tier1: 9 + I corruption damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 14 + I corruption damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 19 + I corruption damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---


*You bend the fate of a foe, willing them to die.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**          | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 9 + I corruption damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **12-16:** 14 + I corruption damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 19 + I corruption damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

**Effect:** If this damage kills the target, you and each ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
