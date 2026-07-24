---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: 2 burst
effects:
    - effect: This ability targets only enemies with line of effect to your companion.
      name: Special
    - effect: Your companion [shifts](../../../../movement/shifting.md) up to a number of squares equal to their Intuition score. During this movement, they are invisible. They then make a power roll.
      name: Effect
    - roll: Power Roll + Intuition
      tier1: 4 damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 6 damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 10 damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
file_basename: jump-scare
file_dpath: feature/ability/beastheart/level-2
flavor: Surprised to see me?
item_id: jump-scare
item_name: Jump Scare
keywords:
    - Area
    - Companion
    - Magic
level: "2"
name: Jump Scare
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/jump-scare
source: mcdm.beastheart.v1
subclass: prowler
target: Each enemy in the area
tier1: 4 damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
tier2: 6 damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
tier3: 10 damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: 2 burst
effects:
    - effect: This ability targets only enemies with line of effect to your companion.
      name: Special
    - effect: Your companion [shifts](../../../../movement/shifting.md) up to a number of squares equal to their Intuition score. During this movement, they are invisible. They then make a power roll.
      name: Effect
    - roll: Power Roll + Intuition
      tier1: 4 damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 6 damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 10 damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: Surprised to see me?
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: 2 burst
    effects:
        - effect: This ability targets only enemies with line of effect to your companion.
          name: Special
        - effect: Your companion [shifts](../../../../movement/shifting.md) up to a number of squares equal to their Intuition score. During this movement, they are invisible. They then make a power roll.
          name: Effect
        - roll: Power Roll + Intuition
          tier1: 4 damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 6 damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 10 damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    flavor: Surprised to see me?
    keywords:
        - Area
        - Companion
        - Magic
    level: "2"
    name: Jump Scare
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/jump-scare
    subclass: prowler
    target: Each enemy in the area
    tier1: 4 damage; P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 6 damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 10 damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Jump Scare
target: Each enemy in the area
type: feature
usage: Main action
```
