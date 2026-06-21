---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: While [frightened](../../../../condition/frightened.md) this way, if a target who is a leader or solo creature is [winded](../../../../rule/health/winded.md), they take an extra 25 psychic damage. If a target [frightened](../../../../condition/frightened.md) this way is not a leader or solo creature and is [winded](../../../../rule/health/winded.md), they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
feature_type: ability
file_basename: terror-manifest
file_dpath: feature/ability/censor/level-9
flavor: '"I know what you fear."'
item_id: terror-manifest
item_name: Terror Manifest
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "9"
name: Terror Manifest
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-9/terror-manifest
source: mcdm.heroes.v1
target: One creature
tier1: 7 + P psychic damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
tier2: 10 + P psychic damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
tier3: 13 + P psychic damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: While [frightened](../../../../condition/frightened.md) this way, if a target who is a leader or solo creature is [winded](../../../../rule/health/winded.md), they take an extra 25 psychic damage. If a target [frightened](../../../../condition/frightened.md) this way is not a leader or solo creature and is [winded](../../../../rule/health/winded.md), they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 7 + P psychic damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 10 + P psychic damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 13 + P psychic damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: '"I know what you fear."'
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: While [frightened](../../../../condition/frightened.md) this way, if a target who is a leader or solo creature is [winded](../../../../rule/health/winded.md), they take an extra 25 psychic damage. If a target [frightened](../../../../condition/frightened.md) this way is not a leader or solo creature and is [winded](../../../../rule/health/winded.md), they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    flavor: '"I know what you fear."'
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "9"
    name: Terror Manifest
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/terror-manifest
    target: One creature
    tier1: 7 + P psychic damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 10 + P psychic damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 13 + P psychic damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Terror Manifest
target: One creature
type: feature
usage: Main action
```
