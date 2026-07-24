---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + M, R, I, or P lightning damage
      tier2: 8 + M, R, I, or P lightning damage
      tier3: 11 + M, R, I, or P lightning damage
    - effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: spellsword
name: Leaping Lightning
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.spellsword/leaping-lightning
subtype: signature
target: One creature or object
tier1: 5 + M, R, I, or P lightning damage
tier2: 8 + M, R, I, or P lightning damage
tier3: 11 + M, R, I, or P lightning damage
type: ability
---

*Lightning jumps from your weapon as you strike to harm a nearby foe.*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 5 + M, R, I, or P lightning damage
- **12-16:** 8 + M, R, I, or P lightning damage
- **17+:** 11 + M, R, I, or P lightning damage

**Effect:** A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
