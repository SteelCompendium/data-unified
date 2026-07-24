---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You target a number of creatures with this ability determined by the outcome of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). You and your allies are invisible to each target until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Two creatures
      tier2: Three creatures
      tier3: Five creatures
    - effect: The effect ends early if you take damage from an enemy's ability.
      name: Strained
flavor: You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "6"
name: Synaptic Dissipation
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-dissipation
subclass: telepathy
target: Special
tier1: Two creatures
tier2: Three creatures
tier3: Five creatures
type: ability
---


*You manipulate your enemies' minds and make them wonder if you were ever really there in the first place.*

| **Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Telepathy** |   **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------|---------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                       | **🎯 Special** |

**Effect:** You target a number of creatures with this ability determined by the outcome of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). You and your allies are invisible to each target until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** Two creatures
- **12-16:** Three creatures
- **17+:** Five creatures

**Strained:** The effect ends early if you take damage from an enemy's ability.
