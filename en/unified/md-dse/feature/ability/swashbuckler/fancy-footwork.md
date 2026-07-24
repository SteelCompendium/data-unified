---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
      name: Effect
feature_type: ability
file_basename: fancy-footwork
file_dpath: feature/ability/swashbuckler
flavor: All combat is a dance—and you'll be the one leading.
item_id: fancy-footwork
item_name: Fancy Footwork
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: swashbuckler
name: Fancy Footwork
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.swashbuckler/fancy-footwork
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + M or A damage
tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
      name: Effect
feature_type: ability
flavor: All combat is a dance—and you'll be the one leading.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 5 + M or A damage
          tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
          name: Effect
    flavor: All combat is a dance—and you'll be the one leading.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: swashbuckler
    name: Fancy Footwork
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.swashbuckler/fancy-footwork
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 7 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 10 + M or A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Fancy Footwork
target: One creature
type: feature
usage: Main action
```
