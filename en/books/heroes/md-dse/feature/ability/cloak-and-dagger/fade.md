---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: fade
file_dpath: feature/ability/cloak-and-dagger
flavor: A stab, and a few quick, careful steps back.
item_id: fade
item_name: Fade
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: cloak-and-dagger
name: Fade
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.cloak-and-dagger/fade
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
tier2: 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
tier3: 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
      tier2: 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
      tier3: 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
feature_type: ability
flavor: A stab, and a few quick, careful steps back.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: A stab, and a few quick, careful steps back.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: cloak-and-dagger
    name: Fade
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.cloak-and-dagger/fade
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
    tier2: 6 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
    tier3: 8 + M or A damage; you can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
    type: ability
name: Fade
target: One creature
type: feature
usage: Main action
```
