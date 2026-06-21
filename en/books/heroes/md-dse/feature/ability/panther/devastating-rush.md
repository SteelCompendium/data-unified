---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can move up to 3 squares straight toward the target before this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), which deals extra damage equal to the number of squares you move this way.
feature_type: ability
file_basename: devastating-rush
file_dpath: feature/ability/panther
flavor: The faster you move, the harder you hit.
item_id: devastating-rush
item_name: Devastating Rush
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: panther
name: Devastating Rush
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.panther/devastating-rush
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + M or A damage
tier2: 6 + M or A damage
tier3: 13 + M or A damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can move up to 3 squares straight toward the target before this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), which deals extra damage equal to the number of squares you move this way.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 13 + M or A damage
feature_type: ability
flavor: The faster you move, the harder you hit.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can move up to 3 squares straight toward the target before this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), which deals extra damage equal to the number of squares you move this way.
    flavor: The faster you move, the harder you hit.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: panther
    name: Devastating Rush
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.panther/devastating-rush
    subtype: signature
    target: One creature or object
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Devastating Rush
target: One creature or object
type: feature
usage: Main action
```
