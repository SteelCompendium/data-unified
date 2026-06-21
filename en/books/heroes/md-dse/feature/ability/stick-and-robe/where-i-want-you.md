---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
feature_type: ability
file_basename: where-i-want-you
file_dpath: feature/ability/stick-and-robe
flavor: When your stick speaks, your enemy moves.
item_id: where-i-want-you
item_name: Where I Want You
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: stick-and-robe
name: Where I Want You
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.stick-and-robe/where-i-want-you
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 4 + M or A damage
tier2: 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage
      tier2: 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: stick-and-robe
    name: Where I Want You
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.stick-and-robe/where-i-want-you
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage
    tier2: 7 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 10 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Where I Want You
target: One creature
type: feature
usage: Main action
```
