---
action_type: Main action
ancestry: dragon-knight
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: draconian-pride
file_dpath: feature/ability/dragon-knight
flavor: You let loose a mighty roar to shake your foes' spirits.
item_id: draconian-pride
item_name: Draconian Pride
keywords:
    - Area
    - Magic
name: Draconian Pride
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.dragon-knight/draconian-pride
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 damage
tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
type: ability
---

```ds-feature
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 damage
      tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
feature_type: ability
flavor: You let loose a mighty roar to shake your foes' spirits.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    ancestry: dragon-knight
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: You let loose a mighty roar to shake your foes' spirits.
    keywords:
        - Area
        - Magic
    name: Draconian Pride
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.dragon-knight/draconian-pride
    subtype: signature
    target: Each enemy in the area
    tier1: 2 damage
    tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Draconian Pride
target: Each enemy in the area
type: feature
usage: Main action
```
