---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line toward the target after [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
feature_type: ability
file_basename: driving-assault
file_dpath: feature/ability/censor/level-1
flavor: As you force your enemy back with your weapon, you use your faith to stay close.
item_id: driving-assault
item_name: Driving Assault
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Driving Assault
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/driving-assault
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 6 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 9 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line toward the target after [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 6 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 9 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
feature_type: ability
flavor: As you force your enemy back with your weapon, you use your faith to stay close.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 3 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) in a straight line toward the target after [pushing](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    flavor: As you force your enemy back with your weapon, you use your faith to stay close.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Driving Assault
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/driving-assault
    target: One creature or object
    tier1: 3 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 6 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 9 + M damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Driving Assault
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
