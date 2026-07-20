---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: penance
file_dpath: feature/ability/conduit/level-5
flavor: '"If you won''t kneel, the gods will make you."'
item_id: penance
item_name: Penance
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "5"
name: Penance
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 4 corruption damage; I < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier2: 7 corruption damage; I < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier3: 11 corruption damage; I < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 4 corruption damage; I < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier2: 7 corruption damage; I < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier3: 11 corruption damage; I < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
flavor: '"If you won''t kneel, the gods will make you."'
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: '"If you won''t kneel, the gods will make you."'
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "5"
    name: Penance
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
    target: Each enemy in the area
    tier1: 4 corruption damage; I < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    tier2: 7 corruption damage; I < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    tier3: 11 corruption damage; I < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    type: ability
name: Penance
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
