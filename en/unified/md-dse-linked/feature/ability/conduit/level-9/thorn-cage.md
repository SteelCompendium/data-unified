---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: While [restrained](../../../../condition/restrained.md) this way, the target takes 10 damage at the start of each of your [turns](../../../../rule/combat/turn.md).
feature_type: ability
file_basename: thorn-cage
file_dpath: feature/ability/conduit/level-9
flavor: Vines [burst](../../../../rule/combat/burst.md) forth from the ground and bind your foe, slowly closing around them.
item_id: thorn-cage
item_name: Thorn Cage
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "9"
name: Thorn Cage
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/thorn-cage
source: mcdm.heroes.v1
subclass: nature
target: One creature
tier1: 10 + I damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 15 + I damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 21 + I damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: While [restrained](../../../../condition/restrained.md) this way, the target takes 10 damage at the start of each of your [turns](../../../../rule/combat/turn.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 10 + I damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 15 + I damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 21 + I damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: Vines [burst](../../../../rule/combat/burst.md) forth from the ground and bind your foe, slowly closing around them.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 11 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: While [restrained](../../../../condition/restrained.md) this way, the target takes 10 damage at the start of each of your [turns](../../../../rule/combat/turn.md).
    flavor: Vines [burst](../../../../rule/combat/burst.md) forth from the ground and bind your foe, slowly closing around them.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "9"
    name: Thorn Cage
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/thorn-cage
    subclass: nature
    target: One creature
    tier1: 10 + I damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 15 + I damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 21 + I damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Thorn Cage
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
