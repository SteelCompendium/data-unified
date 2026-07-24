---
action_type: Main action
class: beastheart
distance: 1 burst
effects:
    - effect: Your companion moves up to a number of squares equal to their Intuition score straight toward the closest enemy they are aware of, avoiding damaging terrain and ending the movement when they are adjacent to that enemy.
      name: Effect
    - roll: Power Roll + Might
      tier1: 1 + M damage
      tier2: 3 + M damage
      tier3: 4 + M damage
feature_type: ability
file_basename: feral-strike
file_dpath: feature/ability/beastheart/level-1
item_id: feral-strike
item_name: Feral Strike
keywords:
    - Area
    - Companion
    - Melee
    - Strike
    - Weapon
level: "1"
name: Feral Strike
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/feral-strike
source: mcdm.beastheart.v1
subtype: signature
target: Each creature in the area
tier1: 1 + M damage
tier2: 3 + M damage
tier3: 4 + M damage
type: ability
---

```ds-feature
distance: 1 burst
effects:
    - effect: Your companion moves up to a number of squares equal to their Intuition score straight toward the closest enemy they are aware of, avoiding damaging terrain and ending the movement when they are adjacent to that enemy.
      name: Effect
    - roll: Power Roll + Might
      tier1: 1 + M damage
      tier2: 3 + M damage
      tier3: 4 + M damage
feature_type: ability
keywords:
    - Area
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    distance: 1 burst
    effects:
        - effect: Your companion moves up to a number of squares equal to their Intuition score straight toward the closest enemy they are aware of, avoiding damaging terrain and ending the movement when they are adjacent to that enemy.
          name: Effect
        - roll: Power Roll + Might
          tier1: 1 + M damage
          tier2: 3 + M damage
          tier3: 4 + M damage
    keywords:
        - Area
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Feral Strike
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/feral-strike
    subtype: signature
    target: Each creature in the area
    tier1: 1 + M damage
    tier2: 3 + M damage
    tier3: 4 + M damage
    type: ability
name: Feral Strike
target: Each creature in the area
type: feature
usage: Main action
```
