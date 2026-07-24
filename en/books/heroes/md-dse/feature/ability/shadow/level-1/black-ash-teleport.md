---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
distance: Self
effects:
    - effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. If you have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) at your destination, you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed. If you successfully hide using this maneuver, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
    - cost: Spend 1+ Insight
      effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) 1 additional square for each insight spent.
feature_type: ability
file_basename: black-ash-teleport
file_dpath: feature/ability/shadow/level-1
flavor: In a swirl of black ash, you step from one place to another.
item_id: black-ash-teleport
item_name: Black Ash Teleport
keywords:
    - Magic
level: "1"
name: Black Ash Teleport
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/black-ash-teleport
source: mcdm.heroes.v1
subclass: black-ash
target: Self
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. If you have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) at your destination, you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed. If you successfully hide using this maneuver, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
    - cost: Spend 1+ Insight
      effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) 1 additional square for each insight spent.
feature_type: ability
flavor: In a swirl of black ash, you step from one place to another.
keywords:
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    distance: Self
    effects:
        - effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. If you have [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) at your destination, you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed. If you successfully hide using this maneuver, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          name: Effect
        - cost: Spend 1+ Insight
          effect: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) 1 additional square for each insight spent.
    flavor: In a swirl of black ash, you step from one place to another.
    keywords:
        - Magic
    level: "1"
    name: Black Ash Teleport
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/black-ash-teleport
    subclass: black-ash
    target: Self
    type: ability
name: Black Ash Teleport
target: Self
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
