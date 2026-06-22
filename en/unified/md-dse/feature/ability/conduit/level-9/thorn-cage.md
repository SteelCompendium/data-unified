---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, the target takes 10 damage at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: thorn-cage
file_dpath: feature/ability/conduit/level-9
flavor: Vines [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from the ground and bind your foe, slowly closing around them.
item_id: thorn-cage
item_name: Thorn Cage
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "9"
name: Thorn Cage
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/thorn-cage
source: mcdm.heroes.v1
subclass: nature
target: One creature
tier1: 10 + I damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 15 + I damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 21 + I damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 11 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, the target takes 10 damage at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 10 + I damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 15 + I damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 21 + I damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: Vines [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from the ground and bind your foe, slowly closing around them.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: While [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way, the target takes 10 damage at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: Vines [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) forth from the ground and bind your foe, slowly closing around them.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "9"
    name: Thorn Cage
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/thorn-cage
    subclass: nature
    target: One creature
    tier1: 10 + I damage; A < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 15 + I damage; A < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 21 + I damage; A < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Thorn Cage
target: One creature
type: feature
usage: Main action
```
