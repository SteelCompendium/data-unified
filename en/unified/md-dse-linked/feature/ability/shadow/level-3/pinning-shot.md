---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: pinning-shot
file_dpath: feature/ability/shadow/level-3
flavor: One missile—placed well and placed hard.
item_id: pinning-shot
item_name: Pinning Shot
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "3"
name: Pinning Shot
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
source: mcdm.heroes.v1
target: One creature
tier1: 8 + A damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 12 + A damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 16 + A damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 8 + A damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 12 + A damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 16 + A damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: One missile—placed well and placed hard.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: shadow
    cost: 7 Insight
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    flavor: One missile—placed well and placed hard.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "3"
    name: Pinning Shot
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
    target: One creature
    tier1: 8 + A damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 12 + A damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 16 + A damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    type: ability
name: Pinning Shot
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
