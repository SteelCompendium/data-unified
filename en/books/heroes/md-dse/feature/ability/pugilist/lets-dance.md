---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
feature_type: ability
file_basename: lets-dance
file_dpath: feature/ability/pugilist
flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
item_id: lets-dance
item_name: Let's Dance
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: pugilist
name: Let's Dance
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.pugilist/lets-dance
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + M or A damage
tier2: 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
feature_type: ability
flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) into any square the target leaves after you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) them.
    flavor: Keeping your enemies stumbling around the battlefield is second nature to you.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: pugilist
    name: Let's Dance
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.pugilist/lets-dance
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 8 + M or A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Let's Dance
target: One creature
type: feature
usage: Main action
```
