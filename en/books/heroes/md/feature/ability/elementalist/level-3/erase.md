---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 7 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The number of creatures you target with this ability is determined by your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Special
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: One creature
      tier2: Two creatures
      tier3: Three creatures
    - effect: Each target begins to fade from existence (save ends). On their first [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) while fading from existence, a target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). At the end of their first [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). At the end of their second [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they fade from existence for 1 hour, after which they reappear in their original space or the nearest unoccupied space.
      name: Effect
flavor: With a flick of the wrist, you phase creatures out of existence.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
level: "3"
name: Erase
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/erase
target: Special
tier1: One creature
tier2: Two creatures
tier3: Three creatures
type: ability
---


*With a flick of the wrist, you phase creatures out of existence.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Void** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------------|----------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                |  **🎯 Special** |

**Special:** The number of creatures you target with this ability is determined by your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** One creature
- **12-16:** Two creatures
- **17+:** Three creatures

**Effect:** Each target begins to fade from existence (save ends). On their first [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) while fading from existence, a target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). At the end of their first [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). At the end of their second [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they fade from existence for 1 hour, after which they reappear in their original space or the nearest unoccupied space.
