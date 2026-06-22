---
action_type: Maneuver
class: troubadour
distance: 2 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: power-chord
file_dpath: feature/ability/troubadour/level-1
flavor: Your instrument rings true and your music blows everyone away.
item_id: power-chord
item_name: Power Chord
keywords:
    - Area
    - Magic
level: "1"
name: Power Chord
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
source: mcdm.heroes.v1
subclass: virtuoso
target: Each enemy in the area
tier1: '[Push](../../../../movement/forced-movement.md) 1'
tier2: '[Push](../../../../movement/forced-movement.md) 2'
tier3: '[Push](../../../../movement/forced-movement.md) 3'
type: ability
---

```ds-feature
distance: 2 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: '[Push](../../../../movement/forced-movement.md) 1'
      tier2: '[Push](../../../../movement/forced-movement.md) 2'
      tier3: '[Push](../../../../movement/forced-movement.md) 3'
feature_type: ability
flavor: Your instrument rings true and your music blows everyone away.
keywords:
    - Area
    - Magic
metadata:
    action_type: Maneuver
    class: troubadour
    distance: 2 [burst](../../../../rule/combat/burst.md)
    flavor: Your instrument rings true and your music blows everyone away.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Power Chord
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
    subclass: virtuoso
    target: Each enemy in the area
    tier1: '[Push](../../../../movement/forced-movement.md) 1'
    tier2: '[Push](../../../../movement/forced-movement.md) 2'
    tier3: '[Push](../../../../movement/forced-movement.md) 3'
    type: ability
name: Power Chord
target: Each enemy in the area
type: feature
usage: Maneuver
```
