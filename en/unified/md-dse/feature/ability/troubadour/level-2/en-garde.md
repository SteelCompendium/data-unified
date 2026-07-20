---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: The target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you. If they do, you can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
feature_type: ability
file_basename: en-garde
file_dpath: feature/ability/troubadour/level-2
flavor: Wait, it's... Guard! [Turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)! Parry! Dodge! Spin! Thrust! Ha!
item_id: en-garde
item_name: En Garde!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: En Garde!
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
source: mcdm.heroes.v1
subclass: duelist
target: One creature
tier1: 7 + **A** damage
tier2: 11 + **A** damage
tier3: 16 + **A** damage
type: ability
---

```ds-feature
cost: 5 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you. If they do, you can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 7 + **A** damage
      tier2: 11 + **A** damage
      tier3: 16 + **A** damage
feature_type: ability
flavor: Wait, it's... Guard! [Turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)! Parry! Dodge! Spin! Thrust! Ha!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 5 Drama
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you. If they do, you can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
    flavor: Wait, it's... Guard! [Turn](scc.v1:mcdm.heroes.v1/rule.combat/turn)! Parry! Dodge! Spin! Thrust! Ha!
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: En Garde!
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
    subclass: duelist
    target: One creature
    tier1: 7 + **A** damage
    tier2: 11 + **A** damage
    tier3: 16 + **A** damage
    type: ability
name: En Garde!
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
