---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: A target who is not a minion, leader, or solo creature and who is [winded](../../../../rule/health/winded.md) after taking this damage is reduced to 0 [Stamina](../../../../rule/health/stamina.md).
feature_type: ability
file_basename: assassinate
file_dpath: feature/ability/shadow/level-8
flavor: A practiced attack will instantly kill an already weakened foe.
item_id: assassinate
item_name: Assassinate
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Assassinate
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-8/assassinate
source: mcdm.heroes.v1
target: One creature or object
tier1: 12 + A damage
tier2: 18 + A damage
tier3: 24 + A damage
type: ability
---

```ds-feature
cost: 11 Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: A target who is not a minion, leader, or solo creature and who is [winded](../../../../rule/health/winded.md) after taking this damage is reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 12 + A damage
      tier2: 18 + A damage
      tier3: 24 + A damage
feature_type: ability
flavor: A practiced attack will instantly kill an already weakened foe.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: A target who is not a minion, leader, or solo creature and who is [winded](../../../../rule/health/winded.md) after taking this damage is reduced to 0 [Stamina](../../../../rule/health/stamina.md).
    flavor: A practiced attack will instantly kill an already weakened foe.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Assassinate
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-8/assassinate
    target: One creature or object
    tier1: 12 + A damage
    tier2: 18 + A damage
    tier3: 24 + A damage
    type: ability
name: Assassinate
target: One creature or object
type: feature
usage: Main action
```
