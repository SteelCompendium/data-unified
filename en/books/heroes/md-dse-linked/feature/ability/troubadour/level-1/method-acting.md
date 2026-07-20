---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: You can become [bleeding](../../../../condition/bleeding.md) (save ends) to deal an extra 5 corruption damage to the target.
feature_type: ability
file_basename: method-acting
file_dpath: feature/ability/troubadour/level-1
flavor: They're so hurt by your performance, you start to believe it yourself.
item_id: method-acting
item_name: Method Acting
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Method Acting
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/method-acting
source: mcdm.heroes.v1
target: One creature
tier1: 6 + A damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 10 + A damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 14 + A damage; P < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Drama
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can become [bleeding](../../../../condition/bleeding.md) (save ends) to deal an extra 5 corruption damage to the target.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 6 + A damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 10 + A damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 14 + A damage; P < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: They're so hurt by your performance, you start to believe it yourself.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: troubadour
    cost: 5 Drama
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: You can become [bleeding](../../../../condition/bleeding.md) (save ends) to deal an extra 5 corruption damage to the target.
    flavor: They're so hurt by your performance, you start to believe it yourself.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Method Acting
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/method-acting
    target: One creature
    tier1: 6 + A damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 10 + A damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 14 + A damage; P < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Method Acting
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
