---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; push 2; M < WEAK [prone](../../../../condition/prone.md)
      tier2: 5 + M damage; push 3; M < AVERAGE [prone](../../../../condition/prone.md)
      tier3: 8 + M damage; push 4; M < STRONG [prone](../../../../condition/prone.md)
    - effect: If the target is [force moved](../../../../movement/forced-movement.md) at least 1 square, an enemy adjacent to the target at the end of this forced movement is also targeted by this ability's power roll, but they don't trigger this effect.
      name: Effect
feature_type: ability
file_basename: foe-bowling
file_dpath: feature/ability/beastheart/level-2
flavor: Your companion sends one enemy tumbling into another, taking them both out.
item_id: foe-bowling
item_name: Foe Bowling
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
level: "2"
name: Foe Bowling
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/foe-bowling
source: mcdm.beastheart.v1
subclass: punisher
target: One creature
tier1: 3 + M damage; push 2; M < WEAK [prone](../../../../condition/prone.md)
tier2: 5 + M damage; push 3; M < AVERAGE [prone](../../../../condition/prone.md)
tier3: 8 + M damage; push 4; M < STRONG [prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; push 2; M < WEAK [prone](../../../../condition/prone.md)
      tier2: 5 + M damage; push 3; M < AVERAGE [prone](../../../../condition/prone.md)
      tier3: 8 + M damage; push 4; M < STRONG [prone](../../../../condition/prone.md)
    - effect: If the target is [force moved](../../../../movement/forced-movement.md) at least 1 square, an enemy adjacent to the target at the end of this forced movement is also targeted by this ability's power roll, but they don't trigger this effect.
      name: Effect
feature_type: ability
flavor: Your companion sends one enemy tumbling into another, taking them both out.
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
    effects:
        - roll: Power Roll + Might
          tier1: 3 + M damage; push 2; M < WEAK [prone](../../../../condition/prone.md)
          tier2: 5 + M damage; push 3; M < AVERAGE [prone](../../../../condition/prone.md)
          tier3: 8 + M damage; push 4; M < STRONG [prone](../../../../condition/prone.md)
        - effect: If the target is [force moved](../../../../movement/forced-movement.md) at least 1 square, an enemy adjacent to the target at the end of this forced movement is also targeted by this ability's power roll, but they don't trigger this effect.
          name: Effect
    flavor: Your companion sends one enemy tumbling into another, taking them both out.
    keywords:
        - Charge
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: Foe Bowling
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/foe-bowling
    subclass: punisher
    target: One creature
    tier1: 3 + M damage; push 2; M < WEAK [prone](../../../../condition/prone.md)
    tier2: 5 + M damage; push 3; M < AVERAGE [prone](../../../../condition/prone.md)
    tier3: 8 + M damage; push 4; M < STRONG [prone](../../../../condition/prone.md)
    type: ability
name: Foe Bowling
target: One creature
type: feature
usage: Main action
```
