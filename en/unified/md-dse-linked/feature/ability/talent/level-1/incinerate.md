---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 fire damage
      tier2: 4 fire damage
      tier3: 6 fire damage
    - effect: A column of fire remains in the area until the start of your next [turn](../../../../rule/combat/turn.md). Each enemy who enters the area for the first time in a [combat round](../../../../rule/combat/combat-round.md) or starts their turn there takes 2 fire damage.
      name: Effect
    - effect: The size of the [cube](../../../../rule/combat/cube.md) increases by 2, but the fire disappears at the end of your [turn](../../../../rule/combat/turn.md).
      name: Strained
feature_type: ability
file_basename: incinerate
file_dpath: feature/ability/talent/level-1
flavor: The air erupts into a column of smokeless flame.
item_id: incinerate
item_name: Incinerate
keywords:
    - Area
    - Fire
    - Psionic
    - Pyrokinesis
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Incinerate
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/incinerate
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 fire damage
tier2: 4 fire damage
tier3: 6 fire damage
type: ability
---

```ds-feature
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 fire damage
      tier2: 4 fire damage
      tier3: 6 fire damage
    - effect: A column of fire remains in the area until the start of your next [turn](../../../../rule/combat/turn.md). Each enemy who enters the area for the first time in a [combat round](../../../../rule/combat/combat-round.md) or starts their turn there takes 2 fire damage.
      name: Effect
    - effect: The size of the [cube](../../../../rule/combat/cube.md) increases by 2, but the fire disappears at the end of your [turn](../../../../rule/combat/turn.md).
      name: Strained
feature_type: ability
flavor: The air erupts into a column of smokeless flame.
keywords:
    - Area
    - Fire
    - Psionic
    - Pyrokinesis
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    effects:
        - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
          tier1: 2 fire damage
          tier2: 4 fire damage
          tier3: 6 fire damage
        - effect: A column of fire remains in the area until the start of your next [turn](../../../../rule/combat/turn.md). Each enemy who enters the area for the first time in a [combat round](../../../../rule/combat/combat-round.md) or starts their turn there takes 2 fire damage.
          name: Effect
        - effect: The size of the [cube](../../../../rule/combat/cube.md) increases by 2, but the fire disappears at the end of your [turn](../../../../rule/combat/turn.md).
          name: Strained
    flavor: The air erupts into a column of smokeless flame.
    keywords:
        - Area
        - Fire
        - Psionic
        - Pyrokinesis
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Incinerate
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/incinerate
    subtype: signature
    target: Each enemy in the area
    tier1: 2 fire damage
    tier2: 4 fire damage
    tier3: 6 fire damage
    type: ability
name: Incinerate
target: Each enemy in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
