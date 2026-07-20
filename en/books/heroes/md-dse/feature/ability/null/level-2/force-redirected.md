---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
feature_type: ability
file_basename: force-redirected
file_dpath: feature/ability/null/level-2
flavor: The force of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) moves your target in a surprising direction.
item_id: force-redirected
item_name: Force Redirected
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Force Redirected
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-2/force-redirected
source: mcdm.heroes.v1
subclass: chronokinetic
target: One creature
tier1: 8 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 12 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 16 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 5 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 8 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 12 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 16 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
feature_type: ability
flavor: The force of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) moves your target in a surprising direction.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 5 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
    flavor: The force of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) moves your target in a surprising direction.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Force Redirected
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-2/force-redirected
    subclass: chronokinetic
    target: One creature
    tier1: 8 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 12 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 16 + A damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Force Redirected
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
