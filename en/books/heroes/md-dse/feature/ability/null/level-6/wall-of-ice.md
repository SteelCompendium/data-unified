---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: 10 wall within 10
effect: You can place this wall in occupied squares, [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area into the nearest unoccupied space of your choice. The wall remains until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). The wall's squares are treated as stone squares for the purpose of damage, and you and allies can move freely through the wall. Each enemy who enters a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the wall and has M < AVERAGE is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends). Each enemy who is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into the wall and has M < AVERAGE is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
feature_type: ability
file_basename: wall-of-ice
file_dpath: feature/ability/null/level-6
flavor: You create a [wall of ice](scc.v1:mcdm.heroes.v1/feature.ability.null.level-6/wall-of-ice).
item_id: wall-of-ice
item_name: Wall of Ice
keywords:
    - Area
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Wall of Ice
scc: mcdm.heroes.v1/feature.ability.null.level-6/wall-of-ice
source: mcdm.heroes.v1
subclass: cryokinetic
target: Special
type: ability
---

```ds-feature
cost: 9 Discipline
distance: 10 wall within 10
effects:
    - effect: You can place this wall in occupied squares, [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area into the nearest unoccupied space of your choice. The wall remains until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). The wall's squares are treated as stone squares for the purpose of damage, and you and allies can move freely through the wall. Each enemy who enters a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the wall and has M < AVERAGE is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends). Each enemy who is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into the wall and has M < AVERAGE is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
feature_type: ability
flavor: You create a [wall of ice](scc.v1:mcdm.heroes.v1/feature.ability.null.level-6/wall-of-ice).
keywords:
    - Area
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 9 Discipline
    distance: 10 wall within 10
    effect: You can place this wall in occupied squares, [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area into the nearest unoccupied space of your choice. The wall remains until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). The wall's squares are treated as stone squares for the purpose of damage, and you and allies can move freely through the wall. Each enemy who enters a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the wall and has M < AVERAGE is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends). Each enemy who is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into the wall and has M < AVERAGE is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
    flavor: You create a [wall of ice](scc.v1:mcdm.heroes.v1/feature.ability.null.level-6/wall-of-ice).
    keywords:
        - Area
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Wall of Ice
    scc: mcdm.heroes.v1/feature.ability.null.level-6/wall-of-ice
    subclass: cryokinetic
    target: Special
    type: ability
name: Wall of Ice
target: Special
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
