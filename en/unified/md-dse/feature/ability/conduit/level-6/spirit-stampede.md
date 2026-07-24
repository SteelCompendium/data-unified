---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 10 x 2 line within 5
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 5 damage; M < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier2: 8 damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier3: 11 damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
file_basename: spirit-stampede
file_dpath: feature/ability/conduit/level-6
flavor: Animal spirits run through the battlefield, trampling your foes.
item_id: spirit-stampede
item_name: Spirit Stampede
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Spirit Stampede
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
source: mcdm.heroes.v1
subclass: nature
target: Each enemy in the area
tier1: 5 damage; M < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier2: 8 damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier3: 11 damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: 10 x 2 line within 5
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 5 damage; M < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier2: 8 damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier3: 11 damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
flavor: Animal spirits run through the battlefield, trampling your foes.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: 10 x 2 line within 5
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 5 damage; M < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
          tier2: 8 damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
          tier3: 11 damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    flavor: Animal spirits run through the battlefield, trampling your foes.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Spirit Stampede
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
    subclass: nature
    target: Each enemy in the area
    tier1: 5 damage; M < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    tier2: 8 damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    tier3: 11 damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    type: ability
name: Spirit Stampede
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
