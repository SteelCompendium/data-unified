---
action_type: Main action
class: beastheart
cost: 7 Ferocity
cost_amount: "7"
cost_resource: Ferocity
distance: Melee 1 or ranged 5
effect: Whenever a target more than 3 squares away from you fails the saving throw while [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, you can pull the target up to a number of squares equal to your Intuition score as a free triggered action.
feature_type: ability
file_basename: jaws-of-death
file_dpath: feature/ability/beastheart/level-3
flavor: Spectral teeth clamp on a foe, chaining them to you and draining their life essence.
item_id: jaws-of-death
item_name: Jaws of Death
keywords:
    - Beastheart
    - Magic
    - Melee
    - Ranged
level: "3"
name: Jaws of Death
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/jaws-of-death
source: mcdm.beastheart.v1
target: One creature
tier1: 7 + I damage; P < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 10 + I damage; P < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 14 + I damage; P < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 7 Ferocity
distance: Melee 1 or ranged 5
effects:
    - effect: Whenever a target more than 3 squares away from you fails the saving throw while [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, you can pull the target up to a number of squares equal to your Intuition score as a free triggered action.
    - roll: Power Roll + Intuition
      tier1: 7 + I damage; P < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 10 + I damage; P < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 14 + I damage; P < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: Spectral teeth clamp on a foe, chaining them to you and draining their life essence.
keywords:
    - Beastheart
    - Magic
    - Melee
    - Ranged
metadata:
    action_type: Main action
    class: beastheart
    cost: 7 Ferocity
    distance: Melee 1 or ranged 5
    effect: Whenever a target more than 3 squares away from you fails the saving throw while [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way, you can pull the target up to a number of squares equal to your Intuition score as a free triggered action.
    flavor: Spectral teeth clamp on a foe, chaining them to you and draining their life essence.
    keywords:
        - Beastheart
        - Magic
        - Melee
        - Ranged
    level: "3"
    name: Jaws of Death
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/jaws-of-death
    target: One creature
    tier1: 7 + I damage; P < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 10 + I damage; P < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 14 + I damage; P < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Jaws of Death
target: One creature
type: feature
usage: Main action
```
