---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 3 Drama
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 4 damage; P < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 5 damage; P < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 6 damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
      name: Effect
flavor: You write something unexpected into the scene that hinders your enemy.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Quick Rewrite
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
target: Each enemy in the area
tier1: 4 damage; P < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 5 damage; P < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 6 damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---


*You write something unexpected into the scene that hinders your enemy.*

| **Area, Magic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)**     |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------|------------------------------:|
| **📏 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10**     | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 4 damage; P < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 5 damage; P < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 6 damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
