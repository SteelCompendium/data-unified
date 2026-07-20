---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy in the area.
feature_type: ability
file_basename: tough-crowd
file_dpath: feature/ability/troubadour/level-2
flavor: Your fans don't seem to like the opening act...
item_id: tough-crowd
item_name: Tough Crowd
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Tough Crowd
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/tough-crowd
source: mcdm.heroes.v1
subclass: virtuoso
target: Special
tier1: 5 corruption damage; M < WEAK, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1 toward the center of the area
tier2: 9 corruption damage; M < AVERAGE, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 toward the center of the area
tier3: 12 corruption damage; M < STRONG, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
type: ability
---

```ds-feature
cost: 5 Drama
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy in the area.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 corruption damage; M < WEAK, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1 toward the center of the area
      tier2: 9 corruption damage; M < AVERAGE, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 toward the center of the area
      tier3: 12 corruption damage; M < STRONG, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
feature_type: ability
flavor: Your fans don't seem to like the opening act...
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 5 Drama
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy in the area.
    flavor: Your fans don't seem to like the opening act...
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Tough Crowd
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/tough-crowd
    subclass: virtuoso
    target: Special
    tier1: 5 corruption damage; M < WEAK, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1 toward the center of the area
    tier2: 9 corruption damage; M < AVERAGE, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 toward the center of the area
    tier3: 12 corruption damage; M < STRONG, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3 toward the center of the area
    type: ability
name: Tough Crowd
target: Special
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
