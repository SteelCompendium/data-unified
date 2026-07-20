---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: penance
file_dpath: feature/ability/conduit/level-5
flavor: '"If you won''t kneel, the gods will make you."'
item_id: penance
item_name: Penance
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "5"
name: Penance
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 4 corruption damage; I < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
tier2: 7 corruption damage; I < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
tier3: 11 corruption damage; I < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 4 corruption damage; I < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
      tier2: 7 corruption damage; I < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
      tier3: 11 corruption damage; I < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
feature_type: ability
flavor: '"If you won''t kneel, the gods will make you."'
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 9 Piety
    distance: 4 [cube](../../../../rule/combat/cube.md) within 10
    flavor: '"If you won''t kneel, the gods will make you."'
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "5"
    name: Penance
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
    target: Each enemy in the area
    tier1: 4 corruption damage; I < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
    tier2: 7 corruption damage; I < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
    tier3: 11 corruption damage; I < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
    type: ability
name: Penance
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
