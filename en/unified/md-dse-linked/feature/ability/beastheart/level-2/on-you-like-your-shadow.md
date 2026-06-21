---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
effect: Your companion enters the target's space. Until your companion is no longer in the target's space, they can end their turn in that space, strikes against them also affect the target, and your strikes against the target gain an edge.
feature_type: ability
file_basename: on-you-like-your-shadow
file_dpath: feature/ability/beastheart/level-2
flavor: Your companion darts around their target, staying out of reach and using them as a shield.
item_id: on-you-like-your-shadow
item_name: On You Like Your Shadow
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
level: "2"
name: On You Like Your Shadow
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/on-you-like-your-shadow
source: mcdm.beastheart.v1
subclass: prowler
target: One creature or object
tier1: 5 + M damage
tier2: 8 + M damage
tier3: 12 + M damage
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - effect: Your companion enters the target's space. Until your companion is no longer in the target's space, they can end their turn in that space, strikes against them also affect the target, and your strikes against the target gain an edge.
    - roll: Power Roll + Might
      tier1: 5 + M damage
      tier2: 8 + M damage
      tier3: 12 + M damage
feature_type: ability
flavor: Your companion darts around their target, staying out of reach and using them as a shield.
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: Melee 1
    effect: Your companion enters the target's space. Until your companion is no longer in the target's space, they can end their turn in that space, strikes against them also affect the target, and your strikes against the target gain an edge.
    flavor: Your companion darts around their target, staying out of reach and using them as a shield.
    keywords:
        - Charge
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: On You Like Your Shadow
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/on-you-like-your-shadow
    subclass: prowler
    target: One creature or object
    tier1: 5 + M damage
    tier2: 8 + M damage
    tier3: 12 + M damage
    type: ability
name: On You Like Your Shadow
target: One creature or object
type: feature
usage: Main action
```
