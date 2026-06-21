---
action_type: Main action
class: censor
distance: 2 [cube](../../../../rule/combat/cube.md) within 1
feature_type: ability
file_basename: back-blasphemer
file_dpath: feature/ability/censor/level-1
flavor: You channel power through your weapon to repel foes.
item_id: back-blasphemer
item_name: Back Blasphemer!
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "1"
name: Back Blasphemer!
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 holy damage; [push](../../../../movement/forced-movement.md) 1
tier2: 4 holy damage; [push](../../../../movement/forced-movement.md) 2
tier3: 6 holy damage; [push](../../../../movement/forced-movement.md) 3
type: ability
---

```ds-feature
distance: 2 [cube](../../../../rule/combat/cube.md) within 1
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 2 holy damage; [push](../../../../movement/forced-movement.md) 1
      tier2: 4 holy damage; [push](../../../../movement/forced-movement.md) 2
      tier3: 6 holy damage; [push](../../../../movement/forced-movement.md) 3
feature_type: ability
flavor: You channel power through your weapon to repel foes.
keywords:
    - Area
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: 2 [cube](../../../../rule/combat/cube.md) within 1
    flavor: You channel power through your weapon to repel foes.
    keywords:
        - Area
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "1"
    name: Back Blasphemer!
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
    subtype: signature
    target: Each enemy in the area
    tier1: 2 holy damage; [push](../../../../movement/forced-movement.md) 1
    tier2: 4 holy damage; [push](../../../../movement/forced-movement.md) 2
    tier3: 6 holy damage; [push](../../../../movement/forced-movement.md) 3
    type: ability
name: Back Blasphemer!
target: Each enemy in the area
type: feature
usage: Main action
```
