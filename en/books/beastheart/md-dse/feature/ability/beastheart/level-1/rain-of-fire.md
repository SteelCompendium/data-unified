---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: 3 cube within 5
effects:
    - roll: Power Roll + Might
      tier1: 3 fire damage
      tier2: 5 fire damage
      tier3: 8 fire damage
    - effect: If your companion is in the area, they deal fire damage equal to their Intuition score to each target.
      name: Effect
feature_type: ability
file_basename: rain-of-fire
file_dpath: feature/ability/beastheart/level-1
flavor: As your arrows rain down on your foes, flames spiral around your companion, setting the arrows ablaze.
item_id: rain-of-fire
item_name: Rain of Fire
keywords:
    - Area
    - Beastheart
    - Weapon
level: "1"
name: Rain of Fire
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/rain-of-fire
source: mcdm.beastheart.v1
target: Each enemy in the area
tier1: 3 fire damage
tier2: 5 fire damage
tier3: 8 fire damage
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: 3 cube within 5
effects:
    - roll: Power Roll + Might
      tier1: 3 fire damage
      tier2: 5 fire damage
      tier3: 8 fire damage
    - effect: If your companion is in the area, they deal fire damage equal to their Intuition score to each target.
      name: Effect
feature_type: ability
flavor: As your arrows rain down on your foes, flames spiral around your companion, setting the arrows ablaze.
keywords:
    - Area
    - Beastheart
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: 3 cube within 5
    effects:
        - roll: Power Roll + Might
          tier1: 3 fire damage
          tier2: 5 fire damage
          tier3: 8 fire damage
        - effect: If your companion is in the area, they deal fire damage equal to their Intuition score to each target.
          name: Effect
    flavor: As your arrows rain down on your foes, flames spiral around your companion, setting the arrows ablaze.
    keywords:
        - Area
        - Beastheart
        - Weapon
    level: "1"
    name: Rain of Fire
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/rain-of-fire
    target: Each enemy in the area
    tier1: 3 fire damage
    tier2: 5 fire damage
    tier3: 8 fire damage
    type: ability
name: Rain of Fire
target: Each enemy in the area
type: feature
usage: Main action
```
