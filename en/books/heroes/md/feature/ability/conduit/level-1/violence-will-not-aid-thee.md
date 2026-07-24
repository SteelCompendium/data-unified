---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 3 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I lightning damage
      tier2: 6 + I lightning damage
      tier3: 9 + I lightning damage
    - effect: The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).
      name: Effect
flavor: After some holy lightning, your enemy will think twice about their next attack.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Violence Will Not Aid Thee
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/violence-will-not-aid-thee
target: One creature
tier1: 3 + I lightning damage
tier2: 6 + I lightning damage
tier3: 9 + I lightning damage
type: ability
---


*After some holy lightning, your enemy will think twice about their next attack.*

| **Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)**  |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**           | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition):**

- **≤11:** 3 + I lightning damage
- **12-16:** 6 + I lightning damage
- **17+:** 9 + I lightning damage

**Effect:** The first time on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).
