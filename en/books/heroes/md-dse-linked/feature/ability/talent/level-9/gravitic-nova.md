---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: On a [critical hit](../../../../rule/combat/critical-hit.md), the size of the area increases by 3, and this ability deals an extra 10 damage.
feature_type: ability
file_basename: gravitic-nova
file_dpath: feature/ability/talent/level-9
flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
item_id: gravitic-nova
item_name: Gravitic Nova
keywords:
    - Area
    - Psionic
    - Telekinesis
level: "9"
name: Gravitic Nova
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-9/gravitic-nova
source: mcdm.heroes.v1
subclass: telekinesis
target: Each enemy and object in the area
tier1: 6 damage; [push](../../../../movement/forced-movement.md) 7
tier2: 9 damage; [push](../../../../movement/forced-movement.md) 10
tier3: 13 damage; [push](../../../../movement/forced-movement.md) 15
type: ability
---

```ds-feature
cost: 11 Clarity
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: On a [critical hit](../../../../rule/combat/critical-hit.md), the size of the area increases by 3, and this ability deals an extra 10 damage.
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 6 damage; [push](../../../../movement/forced-movement.md) 7
      tier2: 9 damage; [push](../../../../movement/forced-movement.md) 10
      tier3: 13 damage; [push](../../../../movement/forced-movement.md) 15
feature_type: ability
flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
keywords:
    - Area
    - Psionic
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effect: On a [critical hit](../../../../rule/combat/critical-hit.md), the size of the area increases by 3, and this ability deals an extra 10 damage.
    flavor: Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.
    keywords:
        - Area
        - Psionic
        - Telekinesis
    level: "9"
    name: Gravitic Nova
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-9/gravitic-nova
    subclass: telekinesis
    target: Each enemy and object in the area
    tier1: 6 damage; [push](../../../../movement/forced-movement.md) 7
    tier2: 9 damage; [push](../../../../movement/forced-movement.md) 10
    tier3: 13 damage; [push](../../../../movement/forced-movement.md) 15
    type: ability
name: Gravitic Nova
target: Each enemy and object in the area
type: feature
usage: Main action
```
