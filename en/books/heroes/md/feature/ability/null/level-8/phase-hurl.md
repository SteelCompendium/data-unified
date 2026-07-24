---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 11 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: The target and each creature or object they collide with from this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way, they see glimpses of creatures from other parts of the timescape.
      name: Effect
flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Phase Hurl
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-8/phase-hurl
target: One creature
tier1: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---


*You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                     | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

**Effect:** The target and each creature or object they collide with from this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way, they see glimpses of creatures from other parts of the timescape.
