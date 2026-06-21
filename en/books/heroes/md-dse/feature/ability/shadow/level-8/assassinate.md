---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: A target who is not a minion, leader, or solo creature and who is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) after taking this damage is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
file_basename: assassinate
file_dpath: feature/ability/shadow/level-8
flavor: A practiced attack will instantly kill an already weakened foe.
item_id: assassinate
item_name: Assassinate
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Assassinate
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: A target who is not a minion, leader, or solo creature and who is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) after taking this damage is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 12 + A damage
      tier2: 18 + A damage
      tier3: 24 + A damage
feature_type: ability
flavor: A practiced attack will instantly kill an already weakened foe.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: A target who is not a minion, leader, or solo creature and who is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) after taking this damage is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    flavor: A practiced attack will instantly kill an already weakened foe.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Assassinate
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
