---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: volcanos-embrace
file_dpath: feature/ability/elementalist/level-2
flavor: Wrap them up in fire and melting stone.
item_id: volcanos-embrace
item_name: Volcano's Embrace
keywords:
    - Earth
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: Volcano's Embrace
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/volcanos-embrace
source: mcdm.heroes.v1
target: One creature
tier1: 5 + R fire damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 9 + R fire damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 12 + R fire damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 5 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 + R fire damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 9 + R fire damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 12 + R fire damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: Wrap them up in fire and melting stone.
keywords:
    - Earth
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 5 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: Wrap them up in fire and melting stone.
    keywords:
        - Earth
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "2"
    name: Volcano's Embrace
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/volcanos-embrace
    target: One creature
    tier1: 5 + R fire damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 9 + R fire damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 12 + R fire damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Volcano's Embrace
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
