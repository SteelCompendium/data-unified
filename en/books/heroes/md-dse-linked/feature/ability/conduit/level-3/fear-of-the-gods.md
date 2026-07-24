---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 6 psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 9 psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 13 psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    - effect: Each target is [frightened](../../../../condition/frightened.md) of you or a creature you choose within [distance](../../../../rule/combat/distance.md).
      name: Effect
feature_type: ability
file_basename: fear-of-the-gods
file_dpath: feature/ability/conduit/level-3
flavor: Your divine magic makes a creature appear as what your enemies fear most.
item_id: fear-of-the-gods
item_name: Fear of the Gods
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "3"
name: Fear of the Gods
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
tier2: 9 psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
tier3: 13 psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 6 psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 9 psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 13 psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    - effect: Each target is [frightened](../../../../condition/frightened.md) of you or a creature you choose within [distance](../../../../rule/combat/distance.md).
      name: Effect
feature_type: ability
flavor: Your divine magic makes a creature appear as what your enemies fear most.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 7 Piety
    distance: 5 [cube](../../../../rule/combat/cube.md) within 10
    effects:
        - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 6 psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 9 psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 13 psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
        - effect: Each target is [frightened](../../../../condition/frightened.md) of you or a creature you choose within [distance](../../../../rule/combat/distance.md).
          name: Effect
    flavor: Your divine magic makes a creature appear as what your enemies fear most.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "3"
    name: Fear of the Gods
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
    target: Each enemy in the area
    tier1: 6 psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 9 psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 13 psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Fear of the Gods
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
