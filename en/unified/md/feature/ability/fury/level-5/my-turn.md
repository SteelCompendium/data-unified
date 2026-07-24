---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: fury
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 9 + M damage
      tier3: 13 + M damage
    - effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
flavor: You quickly strike back at a foe.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: My Turn!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
subtype: triggered
target: The triggering creature
tier1: 6 + M damage
tier2: 9 + M damage
tier3: 13 + M damage
trigger: A creature causes you to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or damages you while you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
type: ability
---


*You quickly strike back at a foe.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |             **Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
|---------------------------|-------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 The triggering creature** |

**Trigger:** A creature causes you to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or damages you while you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 6 + M damage
- **12-16:** 9 + M damage
- **17+:** 13 + M damage

**Effect:** You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
