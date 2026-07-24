---
action_type: Main action
class: beastheart
cost: 7 Ferocity
cost_amount: "7"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 13 + M damage; P < WEAK [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 19 + M damage; P < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 25 + M damage; P < STRONG [dazed](../../../../condition/dazed.md) (save ends)
    - effect: You are [bleeding](../../../../condition/bleeding.md) (save ends). Until the end of your next turn, your companion gains an edge on power rolls.
      name: Effect
feature_type: ability
file_basename: head-to-head
file_dpath: feature/ability/beastheart/level-3
flavor: Your bloody-forehead smash drives your companion into a frenzy.
item_id: head-to-head
item_name: Head to Head
keywords:
    - Beastheart
    - Melee
    - Strike
level: "3"
name: Head to Head
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/head-to-head
source: mcdm.beastheart.v1
target: One creature
tier1: 13 + M damage; P < WEAK [dazed](../../../../condition/dazed.md) (save ends)
tier2: 19 + M damage; P < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
tier3: 25 + M damage; P < STRONG [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 13 + M damage; P < WEAK [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 19 + M damage; P < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 25 + M damage; P < STRONG [dazed](../../../../condition/dazed.md) (save ends)
    - effect: You are [bleeding](../../../../condition/bleeding.md) (save ends). Until the end of your next turn, your companion gains an edge on power rolls.
      name: Effect
feature_type: ability
flavor: Your bloody-forehead smash drives your companion into a frenzy.
keywords:
    - Beastheart
    - Melee
    - Strike
metadata:
    action_type: Main action
    class: beastheart
    cost: 7 Ferocity
    distance: Melee 1
    effects:
        - roll: Power Roll + Might
          tier1: 13 + M damage; P < WEAK [dazed](../../../../condition/dazed.md) (save ends)
          tier2: 19 + M damage; P < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 25 + M damage; P < STRONG [dazed](../../../../condition/dazed.md) (save ends)
        - effect: You are [bleeding](../../../../condition/bleeding.md) (save ends). Until the end of your next turn, your companion gains an edge on power rolls.
          name: Effect
    flavor: Your bloody-forehead smash drives your companion into a frenzy.
    keywords:
        - Beastheart
        - Melee
        - Strike
    level: "3"
    name: Head to Head
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/head-to-head
    target: One creature
    tier1: 13 + M damage; P < WEAK [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 19 + M damage; P < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 25 + M damage; P < STRONG [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Head to Head
target: One creature
type: feature
usage: Main action
```
