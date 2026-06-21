---
action_type: Main action
class: tactician
cost: 5 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: You mark the target.
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Mind Game
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mind-game
target: One creature or object
tier1: 4 + M damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 6 + M damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 10 + M damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---


*Your attack demoralizes your foe. Your allies begin to think you can win.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|-----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature or object** |

**Effect:** You mark the target.

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 4 + M damage; R < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **12-16:** 6 + M damage; R < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 10 + M damage; R < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

**Effect:** Before the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the first time any ally deals damage to any target marked by you, that ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
