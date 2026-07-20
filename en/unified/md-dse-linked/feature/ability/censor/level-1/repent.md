---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: repent
file_dpath: feature/ability/censor/level-1
flavor: You conjure memories of their sins to harry your foes.
item_id: repent
item_name: Repent!
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Repent!
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
source: mcdm.heroes.v1
target: One creature
tier1: 5 + P holy damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 8 + P holy damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 11 + P holy damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 + P holy damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 8 + P holy damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 11 + P holy damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You conjure memories of their sins to harry your foes.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: censor
    cost: 3 Wrath
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: You conjure memories of their sins to harry your foes.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Repent!
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
    target: One creature
    tier1: 5 + P holy damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 8 + P holy damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 11 + P holy damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Repent!
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
