---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + A damage
      tier2: 8 + A damage
      tier3: 11 + A damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), dividing that movement before or after your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) as desired.
      name: Effect
feature_type: ability
file_basename: get-in-get-out
file_dpath: feature/ability/shadow/level-1
flavor: Move unexpectedly, strike fast, and be gone!
item_id: get-in-get-out
item_name: Get In Get Out
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Get In Get Out
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/get-in-get-out
source: mcdm.heroes.v1
target: One creature
tier1: 5 + A damage
tier2: 8 + A damage
tier3: 11 + A damage
type: ability
---

```ds-feature
cost: 3 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + A damage
      tier2: 8 + A damage
      tier3: 11 + A damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), dividing that movement before or after your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) as desired.
      name: Effect
feature_type: ability
flavor: Move unexpectedly, strike fast, and be gone!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 3 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 5 + A damage
          tier2: 8 + A damage
          tier3: 11 + A damage
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), dividing that movement before or after your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) as desired.
          name: Effect
    flavor: Move unexpectedly, strike fast, and be gone!
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Get In Get Out
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/get-in-get-out
    target: One creature
    tier1: 5 + A damage
    tier2: 8 + A damage
    tier3: 11 + A damage
    type: ability
name: Get In Get Out
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
