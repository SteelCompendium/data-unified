---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: Each ally adjacent to the target can use a free triggered action to deal damage to the target equal to their highest characteristic score.
feature_type: ability
file_basename: dogpile
file_dpath: feature/ability/beastheart/level-5
flavor: You and your allies surround your enemy like a pack of wolves, mobbing them and pulling them down.
item_id: dogpile
item_name: Dogpile
keywords:
    - Beastheart
    - Melee
    - Strike
    - Weapon
level: "5"
name: Dogpile
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/dogpile
source: mcdm.beastheart.v1
target: One creature
tier1: 10 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
tier2: 15 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
tier3: 20 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: Each ally adjacent to the target can use a free triggered action to deal damage to the target equal to their highest characteristic score.
    - roll: Power Roll + Might
      tier1: 10 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
      tier2: 15 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
      tier3: 20 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
feature_type: ability
flavor: You and your allies surround your enemy like a pack of wolves, mobbing them and pulling them down.
keywords:
    - Beastheart
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Melee 1
    effect: Each ally adjacent to the target can use a free triggered action to deal damage to the target equal to their highest characteristic score.
    flavor: You and your allies surround your enemy like a pack of wolves, mobbing them and pulling them down.
    keywords:
        - Beastheart
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: Dogpile
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/dogpile
    target: One creature
    tier1: 10 + M damage; M < WEAK [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
    tier2: 15 + M damage; M < AVERAGE [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
    tier3: 20 + M damage; M < STRONG [grabbed](../../../../condition/grabbed.md) and [prone](../../../../condition/prone.md)
    type: ability
name: Dogpile
target: One creature
type: feature
usage: Main action
```
