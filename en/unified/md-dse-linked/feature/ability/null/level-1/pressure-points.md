---
action_type: Main action
class: "null"
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: pressure-points
file_dpath: feature/ability/null/level-1
flavor: You strike at key nerve clusters to leave your foe staggered.
item_id: pressure-points
item_name: Pressure Points
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Pressure Points
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 7 + A damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 9 + A damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 4 + A damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 7 + A damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 9 + A damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: You strike at key nerve clusters to leave your foe staggered.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You strike at key nerve clusters to leave your foe staggered.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Pressure Points
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; A < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 7 + A damage; A < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 9 + A damage; A < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Pressure Points
target: One creature or object
type: feature
usage: Main action
```
