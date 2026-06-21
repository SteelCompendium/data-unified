---
action_type: Main action
class: elementalist
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: meteoric-introduction
file_dpath: feature/ability/elementalist/level-1
flavor: You give your enemy a gentle tap-like an asteroid impact.
item_id: meteoric-introduction
item_name: Meteoric Introduction
keywords:
    - Earth
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Meteoric Introduction
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/meteoric-introduction
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 5 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 8 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 5 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 8 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
feature_type: ability
flavor: You give your enemy a gentle tap-like an asteroid impact.
keywords:
    - Earth
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: You give your enemy a gentle tap-like an asteroid impact.
    keywords:
        - Earth
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Meteoric Introduction
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/meteoric-introduction
    subtype: signature
    target: One creature or object
    tier1: 3 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 5 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 8 + R damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    type: ability
name: Meteoric Introduction
target: One creature or object
type: feature
usage: Main action
```
