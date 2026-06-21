---
action_type: Main action
class: beastheart
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: 2 burst
feature_type: ability
file_basename: bring-the-thunder
file_dpath: feature/ability/beastheart/level-1
flavor: Your companion unleashes a shattering roar, screech, or howl that terrifies your foes—or at least gets their attention.
item_id: bring-the-thunder
item_name: Bring the Thunder
keywords:
    - Area
    - Companion
    - Magic
level: "1"
name: Bring the Thunder
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/bring-the-thunder
source: mcdm.beastheart.v1
spend: '1 Ferocity: This ability also affects a 2 burst originating from you. An enemy in both areas is only affected once.'
target: Each enemy in the area
tier1: 3 sonic damage; push 1; P < WEAK [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
tier2: 5 sonic damage; push 2; P < AVERAGE [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
tier3: 7 sonic damage; push 3; P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: 2 burst
effects:
    - roll: Power Roll + Intuition
      tier1: 3 sonic damage; push 1; P < WEAK [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
      tier2: 5 sonic damage; push 2; P < AVERAGE [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
      tier3: 7 sonic damage; push 3; P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: '1 Ferocity: This ability also affects a 2 burst originating from you. An enemy in both areas is only affected once.'
      name: Spend
feature_type: ability
flavor: Your companion unleashes a shattering roar, screech, or howl that terrifies your foes—or at least gets their attention.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 3 Ferocity
    distance: 2 burst
    flavor: Your companion unleashes a shattering roar, screech, or howl that terrifies your foes—or at least gets their attention.
    keywords:
        - Area
        - Companion
        - Magic
    level: "1"
    name: Bring the Thunder
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/bring-the-thunder
    spend: '1 Ferocity: This ability also affects a 2 burst originating from you. An enemy in both areas is only affected once.'
    target: Each enemy in the area
    tier1: 3 sonic damage; push 1; P < WEAK [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
    tier2: 5 sonic damage; push 2; P < AVERAGE [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends)
    tier3: 7 sonic damage; push 3; P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Bring the Thunder
target: Each enemy in the area
type: feature
usage: Main action
```
