---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: While [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, if a target who is a leader or solo creature is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they take an extra 25 psychic damage. If a target [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way is not a leader or solo creature and is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
file_basename: terror-manifest
file_dpath: feature/ability/censor/level-9
flavor: '"I know what you fear."'
item_id: terror-manifest
item_name: Terror Manifest
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "9"
name: Terror Manifest
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-9/terror-manifest
source: mcdm.heroes.v1
subclass: exorcist
target: One creature
tier1: 7 + P psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 10 + P psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 13 + P psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: While [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, if a target who is a leader or solo creature is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they take an extra 25 psychic damage. If a target [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way is not a leader or solo creature and is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 7 + P psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 10 + P psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 13 + P psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: '"I know what you fear."'
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: While [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, if a target who is a leader or solo creature is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they take an extra 25 psychic damage. If a target [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way is not a leader or solo creature and is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    flavor: '"I know what you fear."'
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "9"
    name: Terror Manifest
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/terror-manifest
    subclass: exorcist
    target: One creature
    tier1: 7 + P psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 10 + P psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 13 + P psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Terror Manifest
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
