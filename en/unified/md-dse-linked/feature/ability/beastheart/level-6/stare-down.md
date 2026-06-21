---
action_type: Maneuver
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Ranged 5
effect: The first time the target uses a move action, main action, maneuver, or triggered action before the start of your next turn, your companion makes the following power roll before the target acts. If the target hasn't acted before the start of your next turn, they are [frightened](../../../../condition/frightened.md) of your companion (save ends).
feature_type: ability
file_basename: stare-down
file_dpath: feature/ability/beastheart/level-6
flavor: Your companion locks eyes with an enemy, imposing their will upon the enemy and daring them to move a muscle.
item_id: stare-down
item_name: Stare Down
keywords:
    - Companion
    - Magic
    - Ranged
level: "6"
name: Stare Down
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/stare-down
source: mcdm.beastheart.v1
subclass: guardian
target: One creature
tier1: 9 + I psychic damage; I < WEAK [weakened](../../../../condition/weakened.md) (save ends)
tier2: 13 + I psychic damage; I < AVERAGE [weakened](../../../../condition/weakened.md) (save ends)
tier3: 18 + I psychic damage; I < STRONG [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Ranged 5
effects:
    - effect: The first time the target uses a move action, main action, maneuver, or triggered action before the start of your next turn, your companion makes the following power roll before the target acts. If the target hasn't acted before the start of your next turn, they are [frightened](../../../../condition/frightened.md) of your companion (save ends).
    - roll: Power Roll + Intuition
      tier1: 9 + I psychic damage; I < WEAK [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 13 + I psychic damage; I < AVERAGE [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 18 + I psychic damage; I < STRONG [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: Your companion locks eyes with an enemy, imposing their will upon the enemy and daring them to move a muscle.
keywords:
    - Companion
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: beastheart
    cost: 9 Ferocity
    distance: Ranged 5
    effect: The first time the target uses a move action, main action, maneuver, or triggered action before the start of your next turn, your companion makes the following power roll before the target acts. If the target hasn't acted before the start of your next turn, they are [frightened](../../../../condition/frightened.md) of your companion (save ends).
    flavor: Your companion locks eyes with an enemy, imposing their will upon the enemy and daring them to move a muscle.
    keywords:
        - Companion
        - Magic
        - Ranged
    level: "6"
    name: Stare Down
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/stare-down
    subclass: guardian
    target: One creature
    tier1: 9 + I psychic damage; I < WEAK [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 13 + I psychic damage; I < AVERAGE [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 18 + I psychic damage; I < STRONG [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Stare Down
target: One creature
type: feature
usage: Maneuver
```
