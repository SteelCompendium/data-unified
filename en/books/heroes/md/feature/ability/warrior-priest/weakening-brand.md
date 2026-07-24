---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + M, R, I, or P holy damage
      tier2: 5 + M, R, I, or P holy damage
      tier3: 8 + M, R, I, or P holy damage
    - effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
flavor: The impact of your weapon brands your target for destruction.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: warrior-priest
name: Weakening Brand
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.warrior-priest/weakening-brand
subtype: signature
target: One creature or object
tier1: 3 + M, R, I, or P holy damage
tier2: 5 + M, R, I, or P holy damage
tier3: 8 + M, R, I, or P holy damage
type: ability
---

*The impact of your weapon brands your target for destruction.*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 3 + M, R, I, or P holy damage
- **12-16:** 5 + M, R, I, or P holy damage
- **17+:** 8 + M, R, I, or P holy damage

**Effect:** Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
