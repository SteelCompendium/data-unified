---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
file_basename: impaled
file_dpath: feature/ability/fury/level-1
flavor: You skewer your enemy like a boar upon a spit.
item_id: impaled
item_name: Impaled!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Impaled!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
source: mcdm.heroes.v1
subtype: signature
target: One creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller
tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: You skewer your enemy like a boar upon a spit.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    flavor: You skewer your enemy like a boar upon a spit.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Impaled!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
    subtype: signature
    target: One creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller
    tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 7 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Impaled!
target: One creature of your [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
