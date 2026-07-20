---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability because it uses a maneuver.)
feature_type: ability
file_basename: instantaneous-excavation
file_dpath: feature/ability/elementalist/level-1
flavor: The surface of the world around you opens up to swallow foes.
item_id: instantaneous-excavation
item_name: Instantaneous Excavation
keywords:
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Instantaneous Excavation
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/instantaneous-excavation
source: mcdm.heroes.v1
target: Special
tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
tier2: The target falls into the hole.
tier3: The target falls into the hole and can't reduce the height of the fall.
type: ability
---

```ds-feature
cost: 5 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability because it uses a maneuver.)
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
      tier2: The target falls into the hole.
      tier3: The target falls into the hole and can't reduce the height of the fall.
feature_type: ability
flavor: The surface of the world around you opens up to swallow foes.
keywords:
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 5 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) with this ability because it uses a maneuver.)
    flavor: The surface of the world around you opens up to swallow foes.
    keywords:
        - Earth
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Instantaneous Excavation
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/instantaneous-excavation
    target: Special
    tier1: The target can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
    tier2: The target falls into the hole.
    tier3: The target falls into the hole and can't reduce the height of the fall.
    type: ability
name: Instantaneous Excavation
target: Special
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
