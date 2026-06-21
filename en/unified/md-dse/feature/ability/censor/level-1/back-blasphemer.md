---
action_type: Main action
class: censor
distance: 2 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
feature_type: ability
file_basename: back-blasphemer
file_dpath: feature/ability/censor/level-1
flavor: You channel power through your weapon to repel foes.
item_id: back-blasphemer
item_name: Back Blasphemer!
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Back Blasphemer!
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 4 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 6 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
distance: 2 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 4 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 6 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: You channel power through your weapon to repel foes.
keywords:
    - Area
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: 2 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
    flavor: You channel power through your weapon to repel foes.
    keywords:
        - Area
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "1"
    name: Back Blasphemer!
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
    subtype: signature
    target: Each enemy in the area
    tier1: 2 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 4 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 6 holy damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Back Blasphemer!
target: Each enemy in the area
type: feature
usage: Main action
```
