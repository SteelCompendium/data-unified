---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: holy-lash
file_dpath: feature/ability/conduit/level-1
flavor: A tendril of divine energy shoots forth to draw in your foe.
item_id: holy-lash
item_name: Holy Lash
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Holy Lash
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/holy-lash
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 5 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 8 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 5 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 8 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
feature_type: ability
flavor: A tendril of divine energy shoots forth to draw in your foe.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: A tendril of divine energy shoots forth to draw in your foe.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Holy Lash
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/holy-lash
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 5 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 8 + I holy damage; vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
    type: ability
name: Holy Lash
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
