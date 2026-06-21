---
action_type: Maneuver
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). Instead, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number equal to the target's [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
file_basename: machinations-of-sound
file_dpath: feature/ability/shadow/level-2
flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
item_id: machinations-of-sound
item_name: Machinations of Sound
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Machinations of Sound
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/machinations-of-sound
source: mcdm.heroes.v1
target: Each creature in the area
tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4'
tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5'
tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7'
type: ability
---

```ds-feature
cost: 5 Insight
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). Instead, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number equal to the target's [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4'
      tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5'
      tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7'
feature_type: ability
flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: shadow
    cost: 5 Insight
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability). Instead, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is reduced by a number equal to the target's [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
    flavor: Illusory sounds make your foes reposition themselves as they cower or investigate the disturbance.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Machinations of Sound
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/machinations-of-sound
    target: Each creature in the area
    tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4'
    tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5'
    tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7'
    type: ability
name: Machinations of Sound
target: Each creature in the area
type: feature
usage: Maneuver
```
