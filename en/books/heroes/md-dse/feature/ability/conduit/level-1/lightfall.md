---
action_type: Main action
class: conduit
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) yourself and each ally in the area to unoccupied spaces in the area.
feature_type: ability
file_basename: lightfall
file_dpath: feature/ability/conduit/level-1
flavor: A rain of holy light scours your enemies and repositions your allies.
item_id: lightfall
item_name: Lightfall
keywords:
    - Area
    - Magic
level: "1"
name: Lightfall
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/lightfall
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 holy damage
tier2: 3 holy damage
tier3: 5 holy damage
type: ability
---

```ds-feature
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) yourself and each ally in the area to unoccupied spaces in the area.
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 holy damage
      tier2: 3 holy damage
      tier3: 5 holy damage
feature_type: ability
flavor: A rain of holy light scours your enemies and repositions your allies.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: conduit
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) yourself and each ally in the area to unoccupied spaces in the area.
    flavor: A rain of holy light scours your enemies and repositions your allies.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Lightfall
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/lightfall
    subtype: signature
    target: Each enemy in the area
    tier1: 2 holy damage
    tier2: 3 holy damage
    tier3: 5 holy damage
    type: ability
name: Lightfall
target: Each enemy in the area
type: feature
usage: Main action
```
