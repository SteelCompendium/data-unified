---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: elementalist
distance: 2 [cube](../../../../rule/combat/cube.md) within 10
effect: The ground beneath the area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
feature_type: ability
file_basename: unquiet-ground
file_dpath: feature/ability/elementalist/level-1
flavor: A sudden storm of detritus assaults your foes and leaves them struggling to move.
item_id: unquiet-ground
item_name: Unquiet Ground
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Unquiet Ground
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/unquiet-ground
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
distance: 2 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: The ground beneath the area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
feature_type: ability
flavor: A sudden storm of detritus assaults your foes and leaves them struggling to move.
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: elementalist
    distance: 2 [cube](../../../../rule/combat/cube.md) within 10
    effect: The ground beneath the area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.
    flavor: A sudden storm of detritus assaults your foes and leaves them struggling to move.
    keywords:
        - Area
        - Earth
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Unquiet Ground
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/unquiet-ground
    subtype: signature
    target: Each enemy in the area
    tier1: 2 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Unquiet Ground
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
