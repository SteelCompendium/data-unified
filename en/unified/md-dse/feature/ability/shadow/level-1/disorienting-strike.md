---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 6 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 10 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
      name: Effect
feature_type: ability
file_basename: disorienting-strike
file_dpath: feature/ability/shadow/level-1
flavor: Your attack leaves them reeling, allowing you to follow up.
item_id: disorienting-strike
item_name: Disorienting Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Disorienting Strike
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/disorienting-strike
source: mcdm.heroes.v1
target: One creature
tier1: 4 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 6 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 10 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 3 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 6 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 10 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
      name: Effect
feature_type: ability
flavor: Your attack leaves them reeling, allowing you to follow up.
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
          tier1: 4 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 6 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 10 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
          name: Effect
    flavor: Your attack leaves them reeling, allowing you to follow up.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Disorienting Strike
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/disorienting-strike
    target: One creature
    tier1: 4 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 6 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 10 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Disorienting Strike
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
