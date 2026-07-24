---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](../../../../rule/combat/distance.md). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](../../../../rule/dice/power-roll.md) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](../../../../rule/combat/critical-hit.md) with this ability because it uses a maneuver.)
      name: Effect
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: The target can [shift](../../../../movement/shifting.md) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
      tier2: The target falls into the hole.
      tier3: The target falls into the hole and can't reduce the height of the fall.
    - effect: At the start of your [turn](../../../../rule/combat/turn.md), you open another hole, making a [power roll](../../../../rule/dice/power-roll.md) against each creature who could fall into the hole when it opens without spending essence.
      name: Persistent 1
feature_type: ability
file_basename: instantaneous-excavation
file_dpath: feature/ability/elementalist/level-1
flavor: The surface of the world around you opens up to swallow foes.
item_id: instantaneous-excavation
item_name: Instantaneous Excavation
keywords:
    - Earth
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Instantaneous Excavation
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/instantaneous-excavation
source: mcdm.heroes.v1
target: Special
tier1: The target can [shift](../../../../movement/shifting.md) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
tier2: The target falls into the hole.
tier3: The target falls into the hole and can't reduce the height of the fall.
type: ability
---

```ds-feature
cost: 5 Essence
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](../../../../rule/combat/distance.md). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](../../../../rule/dice/power-roll.md) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](../../../../rule/combat/critical-hit.md) with this ability because it uses a maneuver.)
      name: Effect
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: The target can [shift](../../../../movement/shifting.md) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
      tier2: The target falls into the hole.
      tier3: The target falls into the hole and can't reduce the height of the fall.
    - effect: At the start of your [turn](../../../../rule/combat/turn.md), you open another hole, making a [power roll](../../../../rule/dice/power-roll.md) against each creature who could fall into the hole when it opens without spending essence.
      name: Persistent 1
feature_type: ability
flavor: The surface of the world around you opens up to swallow foes.
keywords:
    - Earth
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: elementalist
    cost: 5 Essence
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within [distance](../../../../rule/combat/distance.md). You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate [power roll](../../../../rule/dice/power-roll.md) for each creature on the ground above a hole and small enough to fall in. (You can't score a [critical hit](../../../../rule/combat/critical-hit.md) with this ability because it uses a maneuver.)
          name: Effect
        - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
          tier1: The target can [shift](../../../../movement/shifting.md) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
          tier2: The target falls into the hole.
          tier3: The target falls into the hole and can't reduce the height of the fall.
        - effect: At the start of your [turn](../../../../rule/combat/turn.md), you open another hole, making a [power roll](../../../../rule/dice/power-roll.md) against each creature who could fall into the hole when it opens without spending essence.
          name: Persistent 1
    flavor: The surface of the world around you opens up to swallow foes.
    keywords:
        - Earth
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Instantaneous Excavation
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/instantaneous-excavation
    target: Special
    tier1: The target can [shift](../../../../movement/shifting.md) 1 square from the edge of the hole to the nearest unoccupied space of their choice.
    tier2: The target falls into the hole.
    tier3: The target falls into the hole and can't reduce the height of the fall.
    type: ability
name: Instantaneous Excavation
target: Special
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
