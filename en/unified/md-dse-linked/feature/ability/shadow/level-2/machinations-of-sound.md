---
action_type: Maneuver
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effect: This [forced movement](../../../../movement/forced-movement.md) ignores [stability](../../../../rule/character/stability.md). Instead, the [forced movement](../../../../movement/forced-movement.md) is reduced by a number equal to the target's [Intuition](../../../../rule/character/intuition.md) score.
feature_type: ability
file_basename: machinations-of-sound
file_dpath: feature/ability/shadow/level-2
flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
item_id: machinations-of-sound
item_name: Machinations of Sound
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Machinations of Sound
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/machinations-of-sound
source: mcdm.heroes.v1
subclass: harlequin-mask
target: Each creature in the area
tier1: '[Slide](../../../../movement/forced-movement.md) 4'
tier2: '[Slide](../../../../movement/forced-movement.md) 5'
tier3: '[Slide](../../../../movement/forced-movement.md) 7'
type: ability
---

```ds-feature
cost: 5 Insight
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: This [forced movement](../../../../movement/forced-movement.md) ignores [stability](../../../../rule/character/stability.md). Instead, the [forced movement](../../../../movement/forced-movement.md) is reduced by a number equal to the target's [Intuition](../../../../rule/character/intuition.md) score.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: '[Slide](../../../../movement/forced-movement.md) 4'
      tier2: '[Slide](../../../../movement/forced-movement.md) 5'
      tier3: '[Slide](../../../../movement/forced-movement.md) 7'
feature_type: ability
flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Maneuver
    class: shadow
    cost: 5 Insight
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effect: This [forced movement](../../../../movement/forced-movement.md) ignores [stability](../../../../rule/character/stability.md). Instead, the [forced movement](../../../../movement/forced-movement.md) is reduced by a number equal to the target's [Intuition](../../../../rule/character/intuition.md) score.
    flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Machinations of Sound
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/machinations-of-sound
    subclass: harlequin-mask
    target: Each creature in the area
    tier1: '[Slide](../../../../movement/forced-movement.md) 4'
    tier2: '[Slide](../../../../movement/forced-movement.md) 5'
    tier3: '[Slide](../../../../movement/forced-movement.md) 7'
    type: ability
name: Machinations of Sound
target: Each creature in the area
type: feature
usage: Maneuver
```
