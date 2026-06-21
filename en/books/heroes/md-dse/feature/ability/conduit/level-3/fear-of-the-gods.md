---
action_type: Main action
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: Each target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or a creature you choose within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
feature_type: ability
file_basename: fear-of-the-gods
file_dpath: feature/ability/conduit/level-3
flavor: Your divine magic makes a creature appear as what your enemies fear most.
item_id: fear-of-the-gods
item_name: Fear of the Gods
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "3"
name: Fear of the Gods
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 psychic damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 9 psychic damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 13 psychic damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 7 Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: Each target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or a creature you choose within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 6 psychic damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 9 psychic damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 13 psychic damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: Your divine magic makes a creature appear as what your enemies fear most.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: conduit
    cost: 7 Piety
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: Each target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or a creature you choose within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    flavor: Your divine magic makes a creature appear as what your enemies fear most.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "3"
    name: Fear of the Gods
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
    target: Each enemy in the area
    tier1: 6 psychic damage; I < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 9 psychic damage; I < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 13 psychic damage; I < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Fear of the Gods
target: Each enemy in the area
type: feature
usage: Main action
```
