---
action_type: Main action
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: A creature [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by this ability must be moved straight upward.
feature_type: ability
file_basename: black-ash-eruption
file_dpath: feature/ability/shadow/level-6
flavor: Your attack produces a cloud of black ash that launches an enemy into the air.
item_id: black-ash-eruption
item_name: Black Ash Eruption
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Black Ash Eruption
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-6/black-ash-eruption
source: mcdm.heroes.v1
subclass: black-ash
target: One creature
tier1: 3 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier2: 6 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
tier3: 9 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
type: ability
---

```ds-feature
cost: 9 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: A creature [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by this ability must be moved straight upward.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier2: 6 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
      tier3: 9 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
feature_type: ability
flavor: Your attack produces a cloud of black ash that launches an enemy into the air.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 9 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: A creature [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by this ability must be moved straight upward.
    flavor: Your attack produces a cloud of black ash that launches an enemy into the air.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Black Ash Eruption
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-6/black-ash-eruption
    subclass: black-ash
    target: One creature
    tier1: 3 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier2: 6 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
    tier3: 9 + A damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 15
    type: ability
name: Black Ash Eruption
target: One creature
type: feature
usage: Main action
```
