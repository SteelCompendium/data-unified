---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You mark two enemies within 10 squares of you. Each target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You and each target gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
feature_type: ability
file_basename: hustle
file_dpath: feature/ability/tactician/level-6
flavor: You and your allies coordinate to form a new battle line.
item_id: hustle
item_name: Hustle!
keywords:
    - Area
level: "6"
name: Hustle!
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/hustle
source: mcdm.heroes.v1
subclass: mastermind
target: Self and each ally in the area
type: ability
---

```ds-feature
cost: 9 Focus
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You mark two enemies within 10 squares of you. Each target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You and each target gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
feature_type: ability
flavor: You and your allies coordinate to form a new battle line.
keywords:
    - Area
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 9 Focus
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - effect: You mark two enemies within 10 squares of you. Each target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You and each target gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          name: Effect
    flavor: You and your allies coordinate to form a new battle line.
    keywords:
        - Area
    level: "6"
    name: Hustle!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/hustle
    subclass: mastermind
    target: Self and each ally in the area
    type: ability
name: Hustle!
target: Self and each ally in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
