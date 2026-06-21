---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
effect: Your companion can [teleport](../../../../movement/teleport.md) up to 5 squares before and after making the power roll. Instead of grabbing the target, your companion can pick up a target object that is smaller than they are. You can forgo dealing damage with this ability.
feature_type: ability
file_basename: fetch
file_dpath: feature/ability/beastheart/level-2
flavor: Your companion blinks out of existence, returning with a visitor you were particularly hoping to meet.
item_id: fetch
item_name: Fetch!
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
level: "2"
name: Fetch!
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/fetch
source: mcdm.beastheart.v1
subclass: guardian
target: One creature or object
tier1: 6 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md)
tier2: 8 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md)
tier3: 12 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - effect: Your companion can [teleport](../../../../movement/teleport.md) up to 5 squares before and after making the power roll. Instead of grabbing the target, your companion can pick up a target object that is smaller than they are. You can forgo dealing damage with this ability.
    - roll: Power Roll + Might
      tier1: 6 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md)
      tier2: 8 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md)
      tier3: 12 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md)
feature_type: ability
flavor: Your companion blinks out of existence, returning with a visitor you were particularly hoping to meet.
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: Melee 1
    effect: Your companion can [teleport](../../../../movement/teleport.md) up to 5 squares before and after making the power roll. Instead of grabbing the target, your companion can pick up a target object that is smaller than they are. You can forgo dealing damage with this ability.
    flavor: Your companion blinks out of existence, returning with a visitor you were particularly hoping to meet.
    keywords:
        - Companion
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: Fetch!
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/fetch
    subclass: guardian
    target: One creature or object
    tier1: 6 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md)
    tier2: 8 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md)
    tier3: 12 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md)
    type: ability
name: Fetch!
target: One creature or object
type: feature
usage: Main action
```
