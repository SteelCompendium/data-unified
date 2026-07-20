---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: While the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, your abilities that impose [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can still move them.
feature_type: ability
file_basename: sentenced
file_dpath: feature/ability/censor/level-2
flavor: The shock of your condemnation freezes your enemy in their boots.
item_id: sentenced
item_name: Sentenced
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Sentenced
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-2/sentenced
source: mcdm.heroes.v1
subclass: paragon
target: One creature
tier1: 5 + P damage; P < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 9 + P damage; P < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 12 + P damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: While the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, your abilities that impose [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can still move them.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + P damage; P < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 9 + P damage; P < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 12 + P damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: The shock of your condemnation freezes your enemy in their boots.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 5 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: While the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, your abilities that impose [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) can still move them.
    flavor: The shock of your condemnation freezes your enemy in their boots.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Sentenced
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/sentenced
    subclass: paragon
    target: One creature
    tier1: 5 + P damage; P < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 9 + P damage; P < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 12 + P damage; P < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Sentenced
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
