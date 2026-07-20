---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: Targets closest to the center of the area are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) first.
feature_type: ability
file_basename: gravitic-well
file_dpath: feature/ability/talent/level-6
flavor: You bend gravity into a fine point and pull your foes toward it.
item_id: gravitic-well
item_name: Gravitic Well
keywords:
    - Area
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
level: "6"
name: Gravitic Well
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/gravitic-well
source: mcdm.heroes.v1
subclass: telekinesis
target: Each creature and object in the area
tier1: 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
tier2: 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
tier3: 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area
type: ability
---

```ds-feature
cost: 9 Clarity
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: Targets closest to the center of the area are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) first.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
      tier2: 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
      tier3: 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area
feature_type: ability
flavor: You bend gravity into a fine point and pull your foes toward it.
keywords:
    - Area
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: Targets closest to the center of the area are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) first.
    flavor: You bend gravity into a fine point and pull your foes toward it.
    keywords:
        - Area
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Telekinesis
    level: "6"
    name: Gravitic Well
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/gravitic-well
    subclass: telekinesis
    target: Each creature and object in the area
    tier1: 6 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 toward the center of the area
    tier2: 9 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7 toward the center of the area
    tier3: 13 damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10 toward the center of the area
    type: ability
name: Gravitic Well
target: Each creature and object in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
