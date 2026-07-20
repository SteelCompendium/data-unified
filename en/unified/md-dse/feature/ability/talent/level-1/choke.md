---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target up to 2 squares. If the target is made [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
feature_type: ability
file_basename: choke
file_dpath: feature/ability/talent/level-1
flavor: You crush a foe in a telekinetic grip.
item_id: choke
item_name: Choke
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
    - Telekinesis
level: "1"
name: Choke
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/choke
source: mcdm.heroes.v1
target: One creature
tier1: 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 3 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target up to 2 squares. If the target is made [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: You crush a foe in a telekinetic grip.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
    - Telekinesis
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 3 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target up to 2 squares. If the target is made [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
    flavor: You crush a foe in a telekinetic grip.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Strike
        - Telekinesis
    level: "1"
    name: Choke
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/choke
    target: One creature
    tier1: 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Choke
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
