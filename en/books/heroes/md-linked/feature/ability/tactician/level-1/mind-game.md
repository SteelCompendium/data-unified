---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 5 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: You mark the target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    - effect: Before the start of your next [turn](../../../../rule/combat/turn.md), the first time any ally deals damage to any target marked by you, that ally can spend a [Recovery](../../../../rule/health/recoveries.md).
      name: Effect
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Mind Game
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
target: One creature or object
tier1: 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---


*Your attack demoralizes your foe. Your allies begin to think you can win.*

| **[Melee](../../../../rule/combat/melee.md), [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md), Weapon** |               **[Main action](../../../../rule/combat/turn.md)** |
|-----------------------------------|------------------------------:|
| **📏 [Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5**        | **🎯 One creature or object** |

**Effect:** You mark the target.

**[Power Roll](../../../../rule/dice/power-roll.md) + [Might](../../../../rule/character/might.md):**

- **≤11:** 4 + M damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
- **12-16:** 6 + M damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
- **17+:** 10 + M damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)

**Effect:** Before the start of your next [turn](../../../../rule/combat/turn.md), the first time any ally deals damage to any target marked by you, that ally can spend a [Recovery](../../../../rule/health/recoveries.md).
