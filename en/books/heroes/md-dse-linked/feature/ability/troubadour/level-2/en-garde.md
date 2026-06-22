---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: The target can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against you. If they do, you can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against the target.
feature_type: ability
file_basename: en-garde
file_dpath: feature/ability/troubadour/level-2
flavor: Wait, it's... Guard! [Turn](../../../../rule/combat/turn.md)! Parry! Dodge! Spin! Thrust! Ha!
item_id: en-garde
item_name: En Garde!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: En Garde!
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
source: mcdm.heroes.v1
subclass: duelist
target: One creature
tier1: 7 + **A** damage
tier2: 11 + **A** damage
tier3: 16 + **A** damage
type: ability
---

```ds-feature
cost: 5 Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: The target can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against you. If they do, you can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against the target.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 7 + **A** damage
      tier2: 11 + **A** damage
      tier3: 16 + **A** damage
feature_type: ability
flavor: Wait, it's... Guard! [Turn](../../../../rule/combat/turn.md)! Parry! Dodge! Spin! Thrust! Ha!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: The target can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against you. If they do, you can make a [melee](../../../../rule/combat/melee.md) [free strike](../../../common/main-actions/free-strike.md) against the target.
    flavor: Wait, it's... Guard! [Turn](../../../../rule/combat/turn.md)! Parry! Dodge! Spin! Thrust! Ha!
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: En Garde!
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
    subclass: duelist
    target: One creature
    tier1: 7 + **A** damage
    tier2: 11 + **A** damage
    tier3: 16 + **A** damage
    type: ability
name: En Garde!
target: One creature
type: feature
usage: Main action
```
