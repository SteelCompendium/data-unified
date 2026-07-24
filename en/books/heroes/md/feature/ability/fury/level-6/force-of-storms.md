---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: When the target ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), each creature within 2 squares of the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 squares.
      name: Effect
flavor: You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Force of Storms
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/force-of-storms
subclass: berserker
target: One creature
tier1: 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---


*You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 7 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
- **12-16:** 11 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
- **17+:** 16 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7

**Effect:** When the target ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), each creature within 2 squares of the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 squares.
