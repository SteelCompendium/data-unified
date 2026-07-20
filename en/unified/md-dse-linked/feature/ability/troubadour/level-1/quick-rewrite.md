---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effect: The area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
feature_type: ability
file_basename: quick-rewrite
file_dpath: feature/ability/troubadour/level-1
flavor: You write something unexpected into the scene that hinders your enemy.
item_id: quick-rewrite
item_name: Quick Rewrite
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Quick Rewrite
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 4 damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 5 damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 6 damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Drama
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: The area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 4 damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 5 damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 6 damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: You write something unexpected into the scene that hinders your enemy.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 3 Drama
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effect: The area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
    flavor: You write something unexpected into the scene that hinders your enemy.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Quick Rewrite
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
    target: Each enemy in the area
    tier1: 4 damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 5 damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 6 damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Quick Rewrite
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
