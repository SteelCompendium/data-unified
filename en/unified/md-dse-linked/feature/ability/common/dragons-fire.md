---
action_type: Main action
distance: 5 x 1 line within 1
feature_type: ability
file_basename: dragons-fire
file_dpath: feature/ability/common
flavor: You open your maw and unleash hell.
item_id: dragons-fire
item_name: Dragon's Fire
keywords:
    - Area
    - Magic
name: Dragon's Fire
power_roll_characteristic: Your Highest [Characteristic](../../../rule/character/characteristic.md) Score
scc: mcdm.heroes.v1/feature.ability.common/dragons-fire
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 fire damage
tier2: 8 fire damage
tier3: 11 fire damage
type: ability
---

```ds-feature
distance: 5 x 1 line within 1
effects:
    - roll: Power Roll + Your Highest [Characteristic](../../../rule/character/characteristic.md) Score
      tier1: 5 fire damage
      tier2: 8 fire damage
      tier3: 11 fire damage
feature_type: ability
flavor: You open your maw and unleash hell.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    distance: 5 x 1 line within 1
    flavor: You open your maw and unleash hell.
    keywords:
        - Area
        - Magic
    name: Dragon's Fire
    power_roll_characteristic: Your Highest [Characteristic](../../../rule/character/characteristic.md) Score
    scc: mcdm.heroes.v1/feature.ability.common/dragons-fire
    target: Each enemy in the area
    tier1: 5 fire damage
    tier2: 8 fire damage
    tier3: 11 fire damage
    type: ability
name: Dragon's Fire
target: Each enemy in the area
type: feature
usage: Main action
```
