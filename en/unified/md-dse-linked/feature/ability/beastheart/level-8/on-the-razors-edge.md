---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Melee 1 or ranged 5
effect: Your companion can use this ability against an adjacent target, making their own power roll. Both power rolls gain an edge if either of you is [bleeding](../../../../condition/bleeding.md), dying, or winded, and your power roll has a double edge if your companion is dead or otherwise unable to act.
feature_type: ability
file_basename: on-the-razors-edge
file_dpath: feature/ability/beastheart/level-8
flavor: Driven by the pain and desperation of battle, you and your companion spend your last strength in a flurry of wild attacks.
item_id: on-the-razors-edge
item_name: On the Razor's Edge
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "8"
name: On the Razor's Edge
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-8/on-the-razors-edge
source: mcdm.beastheart.v1
target: One creature or object
tier1: 5 + M damage
tier2: 15 + M damage
tier3: 25 + M damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Melee 1 or ranged 5
effects:
    - effect: Your companion can use this ability against an adjacent target, making their own power roll. Both power rolls gain an edge if either of you is [bleeding](../../../../condition/bleeding.md), dying, or winded, and your power roll has a double edge if your companion is dead or otherwise unable to act.
    - roll: Power Roll + Might
      tier1: 5 + M damage
      tier2: 15 + M damage
      tier3: 25 + M damage
feature_type: ability
flavor: Driven by the pain and desperation of battle, you and your companion spend your last strength in a flurry of wild attacks.
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: Melee 1 or ranged 5
    effect: Your companion can use this ability against an adjacent target, making their own power roll. Both power rolls gain an edge if either of you is [bleeding](../../../../condition/bleeding.md), dying, or winded, and your power roll has a double edge if your companion is dead or otherwise unable to act.
    flavor: Driven by the pain and desperation of battle, you and your companion spend your last strength in a flurry of wild attacks.
    keywords:
        - Beastheart
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "8"
    name: On the Razor's Edge
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-8/on-the-razors-edge
    target: One creature or object
    tier1: 5 + M damage
    tier2: 15 + M damage
    tier3: 25 + M damage
    type: ability
name: On the Razor's Edge
target: One creature or object
type: feature
usage: Main action
```
