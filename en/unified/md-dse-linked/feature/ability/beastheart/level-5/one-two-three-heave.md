---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: If your companion is adjacent to the target, this [forced movement](../../../../movement/forced-movement.md) can ignore the target's stability.
feature_type: ability
file_basename: one-two-three-heave
file_dpath: feature/ability/beastheart/level-5
flavor: Harnessing your companion's strength, you send your foe flying.
item_id: one-two-three-heave
item_name: One, Two, Three, Heave
keywords:
    - Beastheart
    - Melee
    - Strike
    - Weapon
level: "5"
name: One, Two, Three, Heave
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/one-two-three-heave
source: mcdm.beastheart.v1
target: One creature
tier1: 10 + M damage; vertical push 4; [prone](../../../../condition/prone.md)
tier2: 15 + M damage; vertical push 6; [prone](../../../../condition/prone.md)
tier3: 20 + M damage; vertical push 8; [prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: If your companion is adjacent to the target, this [forced movement](../../../../movement/forced-movement.md) can ignore the target's stability.
    - roll: Power Roll + Might
      tier1: 10 + M damage; vertical push 4; [prone](../../../../condition/prone.md)
      tier2: 15 + M damage; vertical push 6; [prone](../../../../condition/prone.md)
      tier3: 20 + M damage; vertical push 8; [prone](../../../../condition/prone.md)
feature_type: ability
flavor: Harnessing your companion's strength, you send your foe flying.
keywords:
    - Beastheart
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Melee 1
    effect: If your companion is adjacent to the target, this [forced movement](../../../../movement/forced-movement.md) can ignore the target's stability.
    flavor: Harnessing your companion's strength, you send your foe flying.
    keywords:
        - Beastheart
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: One, Two, Three, Heave
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/one-two-three-heave
    target: One creature
    tier1: 10 + M damage; vertical push 4; [prone](../../../../condition/prone.md)
    tier2: 15 + M damage; vertical push 6; [prone](../../../../condition/prone.md)
    tier3: 20 + M damage; vertical push 8; [prone](../../../../condition/prone.md)
    type: ability
name: One, Two, Three, Heave
target: One creature
type: feature
usage: Main action
```
