---
action_type: Maneuver
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. For each target in addition to you who [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) away from or into a space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an enemy, that enemy takes fire damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score. Additionally, a target who ends this movement in [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if they are observed.
feature_type: ability
file_basename: cinderstorm
file_dpath: feature/ability/shadow/level-6
flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) your friends in a burst of ash and fire.
item_id: cinderstorm
item_name: Cinderstorm
keywords:
    - Magic
level: "6"
name: Cinderstorm
scc: mcdm.heroes.v1/feature.ability.shadow.level-6/cinderstorm
source: mcdm.heroes.v1
subclass: black-ash
target: Self and each ally in the area
type: ability
---

```ds-feature
cost: 9 Insight
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. For each target in addition to you who [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) away from or into a space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an enemy, that enemy takes fire damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score. Additionally, a target who ends this movement in [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if they are observed.
feature_type: ability
flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) your friends in a burst of ash and fire.
keywords:
    - Magic
metadata:
    action_type: Maneuver
    class: shadow
    cost: 9 Insight
    distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. For each target in addition to you who [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) away from or into a space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an enemy, that enemy takes fire damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score. Additionally, a target who ends this movement in [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if they are observed.
    flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) your friends in a burst of ash and fire.
    keywords:
        - Magic
    level: "6"
    name: Cinderstorm
    scc: mcdm.heroes.v1/feature.ability.shadow.level-6/cinderstorm
    subclass: black-ash
    target: Self and each ally in the area
    type: ability
name: Cinderstorm
target: Self and each ally in the area
type: feature
usage: Maneuver
```
