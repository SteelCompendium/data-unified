---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + M, R, I, or P damage
      tier2: 8 + M, R, I, or P damage
      tier3: 11 + M, R, I, or P damage
    - effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
      name: Effect
flavor: Your weapon unleashes psionic energy that reduces your target's weight.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: battlemind
name: Unmooring
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.battlemind/unmooring
subtype: signature
target: One creature
tier1: 5 + M, R, I, or P damage
tier2: 8 + M, R, I, or P damage
tier3: 11 + M, R, I, or P damage
type: ability
---

*Your weapon unleashes psionic energy that reduces your target's weight.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|------------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                     | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 5 + M, R, I, or P damage
- **12-16:** 8 + M, R, I, or P damage
- **17+:** 11 + M, R, I, or P damage

**Effect:** Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
