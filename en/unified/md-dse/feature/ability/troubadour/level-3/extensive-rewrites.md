---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Instead of [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target, you can swap their location with another target as long as each can fit into the other's space. You can't [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) targets into other creatures or objects using this ability.
feature_type: ability
file_basename: extensive-rewrites
file_dpath: feature/ability/troubadour/level-3
flavor: No, this isn't right. That foe was over there!
item_id: extensive-rewrites
item_name: Extensive Rewrites
keywords:
    - Area
    - Magic
level: "3"
name: Extensive Rewrites
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/extensive-rewrites
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; P < WEAK, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; P < AVERAGE, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; P < STRONG, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
type: ability
---

```ds-feature
cost: 7 Drama
distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Instead of [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target, you can swap their location with another target as long as each can fit into the other's space. You can't [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) targets into other creatures or objects using this ability.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; P < WEAK, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
      tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; P < AVERAGE, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
      tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; P < STRONG, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
feature_type: ability
flavor: No, this isn't right. That foe was over there!
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 7 Drama
    distance: 4 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Instead of [sliding](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target, you can swap their location with another target as long as each can fit into the other's space. You can't [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) targets into other creatures or objects using this ability.
    flavor: No, this isn't right. That foe was over there!
    keywords:
        - Area
        - Magic
    level: "3"
    name: Extensive Rewrites
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/extensive-rewrites
    target: Each enemy in the area
    tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; P < WEAK, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
    tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; P < AVERAGE, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
    tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; P < STRONG, this [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores the target''s [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)'
    type: ability
name: Extensive Rewrites
target: Each enemy in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
