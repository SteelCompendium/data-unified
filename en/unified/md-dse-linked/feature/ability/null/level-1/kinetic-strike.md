---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: "null"
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: kinetic-strike
file_dpath: feature/ability/null/level-1
flavor: Your opponent staggers. They cannot ignore you.
item_id: kinetic-strike
item_name: Kinetic Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Kinetic Strike
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
tier2: 5 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 1
tier3: 6 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 2
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 4 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
      tier2: 5 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 1
      tier3: 6 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 2
feature_type: ability
flavor: Your opponent staggers. They cannot ignore you.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: "null"
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: Your opponent staggers. They cannot ignore you.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Kinetic Strike
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    tier2: 5 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 1
    tier3: 6 + A damage; [taunted](../../../../condition/taunted.md) ([EoT](../../../../rule/combat/end-of-turn.md)), [slide](../../../../movement/forced-movement.md) 2
    type: ability
name: Kinetic Strike
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
