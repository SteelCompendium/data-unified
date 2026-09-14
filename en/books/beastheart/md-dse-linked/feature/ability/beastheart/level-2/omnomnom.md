---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
effects:
    - effect: This ability targets only creatures who are [grabbed](../../../../condition/grabbed.md) and are your companion's size or smaller.
      name: Special
      roll: Power Roll + Might
      tier1: 6 + M damage; M < WEAK the target is swallowed
      tier2: 10 + M damage; M < AVERAGE the target is swallowed
      tier3: 14 + M damage; M < STRONG the target is swallowed
    - effect: A swallowed creature shares your companion's space, is [grabbed](../../../../condition/grabbed.md) and [restrained](../../../../condition/restrained.md), and has line of effect only to your companion. Nothing has line of effect to the swallowed creature.
      name: Effect
    - effect: Once per round at the start of your turn, the swallowed creature takes acid damage equal to 1 + your companion's Might score. If the swallowed creature escapes the grab, your companion immediately regurgitates the creature, who lands [prone](../../../../condition/prone.md) in an unoccupied square adjacent to your companion. Your companion can also regurgitate a swallowed creature as a free maneuver. Your companion can have only one creature swallowed at a time.
feature_type: ability
file_basename: omnomnom
file_dpath: feature/ability/beastheart/level-2
flavor: What do you have in your mouth? No! Bad boy!
item_id: omnomnom
item_name: Omnomnom
keywords:
    - Companion
    - Melee
    - Strike
    - Weapon
level: "2"
name: Omnomnom
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/omnomnom
source: mcdm.beastheart.v1
subclass: guardian
target: One creature
tier1: 6 + M damage; M < WEAK the target is swallowed
tier2: 10 + M damage; M < AVERAGE the target is swallowed
tier3: 14 + M damage; M < STRONG the target is swallowed
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - effect: This ability targets only creatures who are [grabbed](../../../../condition/grabbed.md) and are your companion's size or smaller.
      name: Special
      roll: Power Roll + Might
      tier1: 6 + M damage; M < WEAK the target is swallowed
      tier2: 10 + M damage; M < AVERAGE the target is swallowed
      tier3: 14 + M damage; M < STRONG the target is swallowed
    - effect: A swallowed creature shares your companion's space, is [grabbed](../../../../condition/grabbed.md) and [restrained](../../../../condition/restrained.md), and has line of effect only to your companion. Nothing has line of effect to the swallowed creature.
      name: Effect
    - effect: Once per round at the start of your turn, the swallowed creature takes acid damage equal to 1 + your companion's Might score. If the swallowed creature escapes the grab, your companion immediately regurgitates the creature, who lands [prone](../../../../condition/prone.md) in an unoccupied square adjacent to your companion. Your companion can also regurgitate a swallowed creature as a free maneuver. Your companion can have only one creature swallowed at a time.
feature_type: ability
flavor: What do you have in your mouth? No! Bad boy!
keywords:
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
        - effect: This ability targets only creatures who are [grabbed](../../../../condition/grabbed.md) and are your companion's size or smaller.
          name: Special
          roll: Power Roll + Might
          tier1: 6 + M damage; M < WEAK the target is swallowed
          tier2: 10 + M damage; M < AVERAGE the target is swallowed
          tier3: 14 + M damage; M < STRONG the target is swallowed
        - effect: A swallowed creature shares your companion's space, is [grabbed](../../../../condition/grabbed.md) and [restrained](../../../../condition/restrained.md), and has line of effect only to your companion. Nothing has line of effect to the swallowed creature.
          name: Effect
        - effect: Once per round at the start of your turn, the swallowed creature takes acid damage equal to 1 + your companion's Might score. If the swallowed creature escapes the grab, your companion immediately regurgitates the creature, who lands [prone](../../../../condition/prone.md) in an unoccupied square adjacent to your companion. Your companion can also regurgitate a swallowed creature as a free maneuver. Your companion can have only one creature swallowed at a time.
    flavor: What do you have in your mouth? No! Bad boy!
    keywords:
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: Omnomnom
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/omnomnom
    subclass: guardian
    target: One creature
    tier1: 6 + M damage; M < WEAK the target is swallowed
    tier2: 10 + M damage; M < AVERAGE the target is swallowed
    tier3: 14 + M damage; M < STRONG the target is swallowed
    type: ability
name: Omnomnom
target: One creature
type: feature
usage: Main action
```
