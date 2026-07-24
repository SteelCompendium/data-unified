---
action_type: Main action
class: beastheart
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 5 + M damage; push 2
      tier2: 8 + M damage; push 4
      tier3: 11 + M damage; push 6
    - effect: This forced movement can pass through your space but not end there. If the target passes through your space, they fall [prone](../../../../condition/prone.md) and take extra damage equal to your Intuition score.
      name: Effect
feature_type: ability
file_basename: pushover
file_dpath: feature/ability/beastheart/level-1
flavor: You and your companion surround your foe in order to bring them down.
item_id: pushover
item_name: Pushover
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
level: "1"
name: Pushover
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/pushover
source: mcdm.beastheart.v1
target: One creature or object
tier1: 5 + M damage; push 2
tier2: 8 + M damage; push 4
tier3: 11 + M damage; push 6
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 5 + M damage; push 2
      tier2: 8 + M damage; push 4
      tier3: 11 + M damage; push 6
    - effect: This forced movement can pass through your space but not end there. If the target passes through your space, they fall [prone](../../../../condition/prone.md) and take extra damage equal to your Intuition score.
      name: Effect
feature_type: ability
flavor: You and your companion surround your foe in order to bring them down.
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 3 Ferocity
    distance: Melee 1
    effects:
        - roll: Power Roll + Might
          tier1: 5 + M damage; push 2
          tier2: 8 + M damage; push 4
          tier3: 11 + M damage; push 6
        - effect: This forced movement can pass through your space but not end there. If the target passes through your space, they fall [prone](../../../../condition/prone.md) and take extra damage equal to your Intuition score.
          name: Effect
    flavor: You and your companion surround your foe in order to bring them down.
    keywords:
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Pushover
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/pushover
    target: One creature or object
    tier1: 5 + M damage; push 2
    tier2: 8 + M damage; push 4
    tier3: 11 + M damage; push 6
    type: ability
name: Pushover
target: One creature or object
type: feature
usage: Main action
```
