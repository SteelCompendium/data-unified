---
action_type: Main action
class: elementalist
cost: 3 Essence
cost_amount: "3"
cost_resource: Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: behold-the-mystery
file_dpath: feature/ability/elementalist/level-1
flavor: You open a rift into the void to harry your foes.
item_id: behold-the-mystery
item_name: Behold the Mystery
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
level: "1"
name: Behold the Mystery
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/behold-the-mystery
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 psychic damage
tier2: 4 psychic damage
tier3: 6 psychic damage
type: ability
---

```ds-feature
cost: 3 Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 psychic damage
      tier2: 4 psychic damage
      tier3: 6 psychic damage
feature_type: ability
flavor: You open a rift into the void to harry your foes.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
metadata:
    action_type: Main action
    class: elementalist
    cost: 3 Essence
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: You open a rift into the void to harry your foes.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Void
    level: "1"
    name: Behold the Mystery
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/behold-the-mystery
    target: Each enemy in the area
    tier1: 2 psychic damage
    tier2: 4 psychic damage
    tier3: 6 psychic damage
    type: ability
name: Behold the Mystery
target: Each enemy in the area
type: feature
usage: Main action
```
