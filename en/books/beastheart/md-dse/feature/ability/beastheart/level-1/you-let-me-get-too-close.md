---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
effect: If you grab the target while your companion is adjacent to them, your companion can make a melee free strike against the target.
feature_type: ability
file_basename: you-let-me-get-too-close
file_dpath: feature/ability/beastheart/level-1
flavor: The wilderness has no concept of fair play.
item_id: you-let-me-get-too-close
item_name: You Let Me Get Too Close
keywords:
    - Beastheart
    - Charge
    - Melee
    - Strike
    - Weapon
level: "1"
name: You Let Me Get Too Close
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/you-let-me-get-too-close
source: mcdm.beastheart.v1
target: One creature
tier1: 8 + M damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 12 + M damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 16 + M damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - effect: If you grab the target while your companion is adjacent to them, your companion can make a melee free strike against the target.
    - roll: Power Roll + Might
      tier1: 8 + M damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 12 + M damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 16 + M damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: The wilderness has no concept of fair play.
keywords:
    - Beastheart
    - Charge
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: Melee 1
    effect: If you grab the target while your companion is adjacent to them, your companion can make a melee free strike against the target.
    flavor: The wilderness has no concept of fair play.
    keywords:
        - Beastheart
        - Charge
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: You Let Me Get Too Close
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/you-let-me-get-too-close
    target: One creature
    tier1: 8 + M damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 12 + M damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 16 + M damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: You Let Me Get Too Close
target: One creature
type: feature
usage: Main action
```
