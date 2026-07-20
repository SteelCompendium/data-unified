---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 10 x 2 line within 5
feature_type: ability
file_basename: spirit-stampede
file_dpath: feature/ability/conduit/level-6
flavor: Animal spirits run through the battlefield, trampling your foes.
item_id: spirit-stampede
item_name: Spirit Stampede
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "6"
name: Spirit Stampede
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
source: mcdm.heroes.v1
subclass: nature
target: Each enemy in the area
tier1: 5 damage; M < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
tier2: 8 damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
tier3: 11 damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: 10 x 2 line within 5
effects:
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 5 damage; M < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
      tier2: 8 damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
      tier3: 11 damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
feature_type: ability
flavor: Animal spirits run through the battlefield, trampling your foes.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 9 Piety
    distance: 10 x 2 line within 5
    flavor: Animal spirits run through the battlefield, trampling your foes.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "6"
    name: Spirit Stampede
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
    subclass: nature
    target: Each enemy in the area
    tier1: 5 damage; M < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)
    tier2: 8 damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
    tier3: 11 damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
    type: ability
name: Spirit Stampede
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
