---
action_type: Main action
class: beastheart
distance: Ranged 5
effects:
    - roll: Power Roll + Intuition
      tier1: 2 + I damage
      tier2: 4 + I damage
      tier3: 6 + I damage
    - effect: If the target is not [prone](scc.v1:mcdm.heroes.v1/condition/prone), they must use a free triggered action to fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or take extra damage equal to twice your Intuition score. Your companion can shift up to a number of squares equal to their Intuition score.
      name: Effect
feature_type: ability
file_basename: covering-fire
file_dpath: feature/ability/beastheart/level-1
flavor: Keep your head down, or I'll shoot it off!
item_id: covering-fire
item_name: Covering Fire
keywords:
    - Beastheart
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Covering Fire
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/covering-fire
source: mcdm.beastheart.v1
subtype: signature
target: One creature
tier1: 2 + I damage
tier2: 4 + I damage
tier3: 6 + I damage
type: ability
---

```ds-feature
distance: Ranged 5
effects:
    - roll: Power Roll + Intuition
      tier1: 2 + I damage
      tier2: 4 + I damage
      tier3: 6 + I damage
    - effect: If the target is not [prone](scc.v1:mcdm.heroes.v1/condition/prone), they must use a free triggered action to fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or take extra damage equal to twice your Intuition score. Your companion can shift up to a number of squares equal to their Intuition score.
      name: Effect
feature_type: ability
flavor: Keep your head down, or I'll shoot it off!
keywords:
    - Beastheart
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    distance: Ranged 5
    effects:
        - roll: Power Roll + Intuition
          tier1: 2 + I damage
          tier2: 4 + I damage
          tier3: 6 + I damage
        - effect: If the target is not [prone](scc.v1:mcdm.heroes.v1/condition/prone), they must use a free triggered action to fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or take extra damage equal to twice your Intuition score. Your companion can shift up to a number of squares equal to their Intuition score.
          name: Effect
    flavor: Keep your head down, or I'll shoot it off!
    keywords:
        - Beastheart
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Covering Fire
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/covering-fire
    subtype: signature
    target: One creature
    tier1: 2 + I damage
    tier2: 4 + I damage
    tier3: 6 + I damage
    type: ability
name: Covering Fire
target: One creature
type: feature
usage: Main action
```
