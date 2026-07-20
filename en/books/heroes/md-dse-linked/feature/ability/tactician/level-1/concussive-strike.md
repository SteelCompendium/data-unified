---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: concussive-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your precise strike leaves your foe struggling to respond.
item_id: concussive-strike
item_name: Concussive Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Concussive Strike
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: Your precise strike leaves your foe struggling to respond.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 3 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    flavor: Your precise strike leaves your foe struggling to respond.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Concussive Strike
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Concussive Strike
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
