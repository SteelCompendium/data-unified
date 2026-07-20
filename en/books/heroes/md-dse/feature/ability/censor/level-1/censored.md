---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: When a target who is not a leader or solo creature is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
file_basename: censored
file_dpath: feature/ability/censor/level-1
flavor: Judged and [sentenced](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
item_id: censored
item_name: Censored
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Censored
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: When a target who is not a leader or solo creature is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M holy damage
      tier2: 3 + M holy damage
      tier3: 5 + M holy damage
feature_type: ability
flavor: Judged and [sentenced](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 5 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: When a target who is not a leader or solo creature is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
    flavor: Judged and [sentenced](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Censored
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
    target: One creature
    tier1: 2 + M holy damage
    tier2: 3 + M holy damage
    tier3: 5 + M holy damage
    type: ability
name: Censored
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
