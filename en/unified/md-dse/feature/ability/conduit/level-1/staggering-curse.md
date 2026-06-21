---
action_type: Main action
class: conduit
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: staggering-curse
file_dpath: feature/ability/conduit/level-1
flavor: A blast of judgment disorients your foe.
item_id: staggering-curse
item_name: Staggering Curse
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Staggering Curse
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 5 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 8 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 5 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 8 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: A blast of judgment disorients your foe.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: A blast of judgment disorients your foe.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Staggering Curse
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 5 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 8 + I holy damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Staggering Curse
target: One creature or object
type: feature
usage: Main action
```
