---
action_type: Maneuver
class: troubadour
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
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
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
type: ability
---

```ds-feature
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
      tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
      tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
feature_type: ability
flavor: Your instrument rings true and your music blows everyone away.
keywords:
    - Area
    - Magic
metadata:
    action_type: Maneuver
    class: troubadour
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: Your instrument rings true and your music blows everyone away.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Power Chord
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
    target: Each enemy in the area
    tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1'
    tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
    tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3'
    type: ability
name: Power Chord
target: Each enemy in the area
type: feature
usage: Maneuver
```
