---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). While [flying](scc.v1:mcdm.heroes.v1/movement/fly), a target's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
      name: Effect
    - cost: Spend 5 Clarity
      effect: The effects last for 1 hour instead.
feature_type: ability
file_basename: levitation-field
file_dpath: feature/ability/talent/level-8
flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
item_id: levitation-field
item_name: Levitation Field
keywords:
    - Area
    - Psionic
level: "8"
name: Levitation Field
scc: mcdm.heroes.v1/feature.ability.talent.level-8/levitation-field
source: mcdm.heroes.v1
subclass: telekinesis
target: Each ally in the area
type: ability
---

```ds-feature
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). While [flying](scc.v1:mcdm.heroes.v1/movement/fly), a target's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
      name: Effect
    - cost: Spend 5 Clarity
      effect: The effects last for 1 hour instead.
feature_type: ability
flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
keywords:
    - Area
    - Psionic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - effect: Each target can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). While [flying](scc.v1:mcdm.heroes.v1/movement/fly), a target's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
          name: Effect
        - cost: Spend 5 Clarity
          effect: The effects last for 1 hour instead.
    flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
    keywords:
        - Area
        - Psionic
    level: "8"
    name: Levitation Field
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/levitation-field
    subclass: telekinesis
    target: Each ally in the area
    type: ability
name: Levitation Field
target: Each ally in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
