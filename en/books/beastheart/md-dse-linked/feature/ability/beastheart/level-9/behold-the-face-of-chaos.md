---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Melee 1
effect: Your companion [teleports](../../../../movement/teleport.md) up to their speed.
feature_type: ability
file_basename: behold-the-face-of-chaos
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion appears next to their victim in the guise of a heart-stopping nightmare.
item_id: behold-the-face-of-chaos
item_name: Behold the Face of Chaos
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
level: "9"
name: Behold the Face of Chaos
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/behold-the-face-of-chaos
source: mcdm.beastheart.v1
subclass: prowler
target: One creature
tier1: 13 + I psychic damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
tier2: 20 + I psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
tier3: 27 + I psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Melee 1
effects:
    - effect: Your companion [teleports](../../../../movement/teleport.md) up to their speed.
    - roll: Power Roll + Intuition
      tier1: 13 + I psychic damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 20 + I psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 27 + I psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: Your companion appears next to their victim in the guise of a heart-stopping nightmare.
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: Melee 1
    effect: Your companion [teleports](../../../../movement/teleport.md) up to their speed.
    flavor: Your companion appears next to their victim in the guise of a heart-stopping nightmare.
    keywords:
        - Companion
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Behold the Face of Chaos
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/behold-the-face-of-chaos
    subclass: prowler
    target: One creature
    tier1: 13 + I psychic damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 20 + I psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 27 + I psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Behold the Face of Chaos
target: One creature
type: feature
usage: Main action
```
