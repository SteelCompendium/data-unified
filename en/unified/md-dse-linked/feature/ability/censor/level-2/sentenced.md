---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: While the target is [restrained](../../../../condition/restrained.md) this way, your abilities that impose [forced movement](../../../../movement/forced-movement.md) can still move them.
feature_type: ability
file_basename: sentenced
file_dpath: feature/ability/censor/level-2
flavor: The shock of your condemnation freezes your enemy in their boots.
item_id: sentenced
item_name: Sentenced
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: Sentenced
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-2/sentenced
source: mcdm.heroes.v1
subclass: paragon
target: One creature
tier1: 5 + P damage; P < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 9 + P damage; P < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 12 + P damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: While the target is [restrained](../../../../condition/restrained.md) this way, your abilities that impose [forced movement](../../../../movement/forced-movement.md) can still move them.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 + P damage; P < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 9 + P damage; P < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 12 + P damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: The shock of your condemnation freezes your enemy in their boots.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: censor
    cost: 5 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: While the target is [restrained](../../../../condition/restrained.md) this way, your abilities that impose [forced movement](../../../../movement/forced-movement.md) can still move them.
    flavor: The shock of your condemnation freezes your enemy in their boots.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: Sentenced
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/sentenced
    subclass: paragon
    target: One creature
    tier1: 5 + P damage; P < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 9 + P damage; P < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 12 + P damage; P < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Sentenced
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
