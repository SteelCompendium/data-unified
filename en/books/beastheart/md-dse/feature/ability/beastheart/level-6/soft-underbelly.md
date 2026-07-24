---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 2
effects:
    - roll: Power Roll + Might
      tier1: 10 + M damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 15 + M damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 20 + M damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target has damage weakness 5.
      name: Effect
feature_type: ability
file_basename: soft-underbelly
file_dpath: feature/ability/beastheart/level-6
flavor: Your companion ducks under your enemy's guard and rakes open their soft vitals, leaving them vulnerable.
item_id: soft-underbelly
item_name: Soft Underbelly
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
level: "6"
name: Soft Underbelly
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/soft-underbelly
source: mcdm.beastheart.v1
subclass: prowler
target: One creature
tier1: 10 + M damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 15 + M damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 20 + M damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 2
effects:
    - roll: Power Roll + Might
      tier1: 10 + M damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 15 + M damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 20 + M damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target has damage weakness 5.
      name: Effect
feature_type: ability
flavor: Your companion ducks under your enemy's guard and rakes open their soft vitals, leaving them vulnerable.
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Melee 2
    effects:
        - roll: Power Roll + Might
          tier1: 10 + M damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 15 + M damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 20 + M damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
        - effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target has damage weakness 5.
          name: Effect
    flavor: Your companion ducks under your enemy's guard and rakes open their soft vitals, leaving them vulnerable.
    keywords:
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Soft Underbelly
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/soft-underbelly
    subclass: prowler
    target: One creature
    tier1: 10 + M damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier2: 15 + M damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier3: 20 + M damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Soft Underbelly
target: One creature
type: feature
usage: Main action
```
