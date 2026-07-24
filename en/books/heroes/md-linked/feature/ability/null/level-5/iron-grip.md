---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: "null"
cost: 9 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
      tier2: 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
      tier3: 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)
    - effect: While [grabbed](../../../../condition/grabbed.md) this way, the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../common/maneuvers/escape-grab.md) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](../../../../rule/character/agility.md) score.
      name: Effect
flavor: You grab the target with [supernatural](../../../../rule/general/supernatural.md) force.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Iron Grip
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
target: One creature
tier1: 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
tier2: 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
tier3: 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)
type: ability
---


*You grab the target with [supernatural](../../../../rule/general/supernatural.md) force.*

| **[Melee](../../../../rule/combat/melee.md), Psionic, [Strike](../../../../rule/combat/strike.md), Weapon** |     **[Main action](../../../../rule/combat/turn.md)** |
|------------------------------------|--------------------:|
| **📏 [Melee](../../../../rule/combat/melee.md) 1**                     | **🎯 One creature** |

**[Power Roll](../../../../rule/dice/power-roll.md) + [Agility](../../../../rule/character/agility.md):**

- **≤11:** 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
- **12-16:** 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
- **17+:** 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)

**Effect:** While [grabbed](../../../../condition/grabbed.md) this way, the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../common/maneuvers/escape-grab.md) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](../../../../rule/character/agility.md) score.
