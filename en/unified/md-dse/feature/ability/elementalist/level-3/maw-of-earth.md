---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 7 Essence
cost_amount: "7"
cost_resource: Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: The ground in or directly beneath the area drops 3 squares.
feature_type: ability
file_basename: maw-of-earth
file_dpath: feature/ability/elementalist/level-3
flavor: You open up the ground, spewing out shrapnel of stone and debris.
item_id: maw-of-earth
item_name: Maw of Earth
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "3"
name: Maw of Earth
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/maw-of-earth
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 damage
tier2: 9 damage
tier3: 12 damage
type: ability
---

```ds-feature
cost: 7 Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: The ground in or directly beneath the area drops 3 squares.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 damage
      tier2: 9 damage
      tier3: 12 damage
feature_type: ability
flavor: You open up the ground, spewing out shrapnel of stone and debris.
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 7 Essence
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: The ground in or directly beneath the area drops 3 squares.
    flavor: You open up the ground, spewing out shrapnel of stone and debris.
    keywords:
        - Area
        - Earth
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "3"
    name: Maw of Earth
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/maw-of-earth
    target: Each enemy in the area
    tier1: 5 damage
    tier2: 9 damage
    tier3: 12 damage
    type: ability
name: Maw of Earth
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
