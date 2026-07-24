---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 10 + M damage; vertical push 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 15 + M damage; vertical push 6; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 20 + M damage; vertical push 8; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: If your companion is adjacent to the target, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can ignore the target's stability.
      name: Effect
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
tier1: 10 + M damage; vertical push 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 15 + M damage; vertical push 6; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 20 + M damage; vertical push 8; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 10 + M damage; vertical push 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 15 + M damage; vertical push 6; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 20 + M damage; vertical push 8; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: If your companion is adjacent to the target, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can ignore the target's stability.
      name: Effect
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
    effects:
        - roll: Power Roll + Might
          tier1: 10 + M damage; vertical push 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 15 + M damage; vertical push 6; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 20 + M damage; vertical push 8; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
        - effect: If your companion is adjacent to the target, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can ignore the target's stability.
          name: Effect
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
    tier1: 10 + M damage; vertical push 4; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 15 + M damage; vertical push 6; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 20 + M damage; vertical push 8; [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: One, Two, Three, Heave
target: One creature
type: feature
usage: Main action
```
