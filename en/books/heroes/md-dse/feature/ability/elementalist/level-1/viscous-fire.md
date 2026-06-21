---
action_type: Main action
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: viscous-fire
file_dpath: feature/ability/elementalist/level-1
flavor: A jet of heavy fire erupts where you strike.
item_id: viscous-fire
item_name: Viscous Fire
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Viscous Fire
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/viscous-fire
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 5 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 7 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 5 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 7 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
feature_type: ability
flavor: A jet of heavy fire erupts where you strike.
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: A jet of heavy fire erupts where you strike.
    keywords:
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Viscous Fire
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/viscous-fire
    subtype: signature
    target: One creature or object
    tier1: 2 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 5 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 7 + R fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    type: ability
name: Viscous Fire
target: One creature or object
type: feature
usage: Main action
```
