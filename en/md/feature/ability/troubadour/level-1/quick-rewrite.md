---
action_type: Main action
class: troubadour
cost: 3 Drama
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
flavor: You write something unexpected into the scene that hinders your enemy.
keywords:
    - Area
    - Magic
    - Ranged
level: "1"
name: Quick Rewrite
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
target: Each enemy in the area
type: ability
---


*You write something unexpected into the scene that hinders your enemy.*

| **Area, Magic, Ranged**     |               **Main action** |
|-----------------------------|------------------------------:|
| **📏 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10**     | **🎯 Each enemy in the area** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 4 damage; P < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 5 damage; P < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 6 damage; P < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
