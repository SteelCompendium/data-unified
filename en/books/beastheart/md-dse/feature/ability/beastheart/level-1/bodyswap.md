---
action_type: Main action
class: beastheart
distance: Melee 1
effect: If you and a willing ally are standing on the ground within 10 squares of each other, you can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to swap places. If you do, you gain an edge on this ability.
feature_type: ability
file_basename: bodyswap
file_dpath: feature/ability/beastheart/level-1
flavor: You and your ally morph into each other, magically switching places.
item_id: bodyswap
item_name: Bodyswap
keywords:
    - Beastheart
    - Magic
    - Melee
    - Strike
    - Weapon
level: "1"
name: Bodyswap
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/bodyswap
source: mcdm.beastheart.v1
subtype: signature
target: One creature or object
tier1: 3 + I damage
tier2: 5 + I damage
tier3: 7 + I damage
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: If you and a willing ally are standing on the ground within 10 squares of each other, you can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to swap places. If you do, you gain an edge on this ability.
    - roll: Power Roll + Intuition
      tier1: 3 + I damage
      tier2: 5 + I damage
      tier3: 7 + I damage
feature_type: ability
flavor: You and your ally morph into each other, magically switching places.
keywords:
    - Beastheart
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    distance: Melee 1
    effect: If you and a willing ally are standing on the ground within 10 squares of each other, you can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to swap places. If you do, you gain an edge on this ability.
    flavor: You and your ally morph into each other, magically switching places.
    keywords:
        - Beastheart
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Bodyswap
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/bodyswap
    subtype: signature
    target: One creature or object
    tier1: 3 + I damage
    tier2: 5 + I damage
    tier3: 7 + I damage
    type: ability
name: Bodyswap
target: One creature or object
type: feature
usage: Main action
```
