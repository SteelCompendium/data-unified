---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: When a target who is not a leader or solo creature is made [winded](../../../../rule/health/winded.md) by this ability, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
feature_type: ability
file_basename: censored
file_dpath: feature/ability/censor/level-1
flavor: Judged and [sentenced](../level-2/sentenced.md).
item_id: censored
item_name: Censored
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Censored
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
source: mcdm.heroes.v1
target: One creature
tier1: 2 + M holy damage
tier2: 3 + M holy damage
tier3: 5 + M holy damage
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: When a target who is not a leader or solo creature is made [winded](../../../../rule/health/winded.md) by this ability, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 2 + M holy damage
      tier2: 3 + M holy damage
      tier3: 5 + M holy damage
feature_type: ability
flavor: Judged and [sentenced](../level-2/sentenced.md).
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: When a target who is not a leader or solo creature is made [winded](../../../../rule/health/winded.md) by this ability, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    flavor: Judged and [sentenced](../level-2/sentenced.md).
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Censored
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
    target: One creature
    tier1: 2 + M holy damage
    tier2: 3 + M holy damage
    tier3: 5 + M holy damage
    type: ability
name: Censored
target: One creature
type: feature
usage: Main action
```
