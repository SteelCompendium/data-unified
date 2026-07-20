---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can become [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends) to deal an extra 5 corruption damage to the target.
feature_type: ability
file_basename: method-acting
file_dpath: feature/ability/troubadour/level-1
flavor: They're so hurt by your performance, you start to believe it yourself.
item_id: method-acting
item_name: Method Acting
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Method Acting
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/method-acting
source: mcdm.heroes.v1
target: One creature
tier1: 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 5 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can become [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends) to deal an extra 5 corruption damage to the target.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: They're so hurt by your performance, you start to believe it yourself.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 5 Drama
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can become [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends) to deal an extra 5 corruption damage to the target.
    flavor: They're so hurt by your performance, you start to believe it yourself.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Method Acting
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/method-acting
    target: One creature
    tier1: 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Method Acting
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
