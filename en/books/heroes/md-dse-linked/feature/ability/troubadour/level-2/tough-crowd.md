---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](../../../../rule/combat/turn.md), you can make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy in the area.
feature_type: ability
file_basename: tough-crowd
file_dpath: feature/ability/troubadour/level-2
flavor: Your fans don't seem to like the opening act...
item_id: tough-crowd
item_name: Tough Crowd
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Tough Crowd
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/tough-crowd
source: mcdm.heroes.v1
target: Special
tier1: 5 corruption damage; M < WEAK, [pull](../../../../movement/forced-movement.md) 1 toward the center of the area
tier2: 9 corruption damage; M < AVERAGE, [pull](../../../../movement/forced-movement.md) 2 toward the center of the area
tier3: 12 corruption damage; M < STRONG, [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
type: ability
---

```ds-feature
cost: 5 Drama
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](../../../../rule/combat/turn.md), you can make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy in the area.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 corruption damage; M < WEAK, [pull](../../../../movement/forced-movement.md) 1 toward the center of the area
      tier2: 9 corruption damage; M < AVERAGE, [pull](../../../../movement/forced-movement.md) 2 toward the center of the area
      tier3: 12 corruption damage; M < STRONG, [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
feature_type: ability
flavor: Your fans don't seem to like the opening act...
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](../../../../rule/combat/turn.md), you can make one [power roll](../../../../rule/dice/power-roll.md) that targets each enemy in the area.
    flavor: Your fans don't seem to like the opening act...
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Tough Crowd
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/tough-crowd
    target: Special
    tier1: 5 corruption damage; M < WEAK, [pull](../../../../movement/forced-movement.md) 1 toward the center of the area
    tier2: 9 corruption damage; M < AVERAGE, [pull](../../../../movement/forced-movement.md) 2 toward the center of the area
    tier3: 12 corruption damage; M < STRONG, [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
    type: ability
name: Tough Crowd
target: Special
type: feature
usage: Main action
```
