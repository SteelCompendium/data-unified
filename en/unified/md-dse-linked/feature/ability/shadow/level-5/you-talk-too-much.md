---
action_type: Main action
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effect: The target can't communicate with anyone until the end of the encounter.
feature_type: ability
file_basename: you-talk-too-much
file_dpath: feature/ability/shadow/level-5
flavor: Silence is a virtue. A knife pinning their mouth shut is the next best thing.
item_id: you-talk-too-much
item_name: You Talk Too Much
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: You Talk Too Much
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-5/you-talk-too-much
source: mcdm.heroes.v1
target: One creature
tier1: 10 + A damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 15 + A damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 21 + A damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: The target can't communicate with anyone until the end of the encounter.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 + A damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 15 + A damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 21 + A damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: Silence is a virtue. A knife pinning their mouth shut is the next best thing.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 9 Insight
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effect: The target can't communicate with anyone until the end of the encounter.
    flavor: Silence is a virtue. A knife pinning their mouth shut is the next best thing.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: You Talk Too Much
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-5/you-talk-too-much
    target: One creature
    tier1: 10 + A damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 15 + A damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 21 + A damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: You Talk Too Much
target: One creature
type: feature
usage: Main action
```
