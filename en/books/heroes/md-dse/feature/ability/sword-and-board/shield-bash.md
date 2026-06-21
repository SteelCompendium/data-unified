---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: shield-bash
file_dpath: feature/ability/sword-and-board
flavor: In your hands, a shield isn't just for protection.
item_id: shield-bash
item_name: Shield Bash
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: sword-and-board
name: Shield Bash
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.sword-and-board/shield-bash
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 4 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 9 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 9 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: In your hands, a shield isn't just for protection.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: In your hands, a shield isn't just for protection.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: sword-and-board
    name: Shield Bash
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.sword-and-board/shield-bash
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 9 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Shield Bash
target: One creature
type: feature
usage: Main action
```
