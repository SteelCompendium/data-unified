---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 9 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    - effect: If a target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, they must make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
      name: Effect
flavor: You confuse your foes, causing them to turn on each other.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Panic in Their Lines
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
subclass: insurgent
target: Two creatures
tier1: 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---


*You confuse your foes, causing them to turn on each other.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |      **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------------|---------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 Two creatures** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 6 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **12-16:** 9 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
- **17+:** 13 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5

**Effect:** If a target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into another creature, they must make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
