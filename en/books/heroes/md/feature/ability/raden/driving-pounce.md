---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage
      tier2: 7 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target.
      name: Effect
flavor: Your enemies try in vain to fall back from your pouncing attack.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: raden
name: Driving Pounce
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.raden/driving-pounce
subtype: signature
target: One creature or object
tier1: 4 + A damage
tier2: 7 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
type: ability
---

*Your enemies try in vain to fall back from your pouncing attack.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + A damage
- **12-16:** 7 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **17+:** 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2

**Effect:** You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target.
