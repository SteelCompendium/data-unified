---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: pressure-points
file_dpath: feature/ability/null/level-1
flavor: You strike at key nerve clusters to leave your foe staggered.
item_id: pressure-points
item_name: Pressure Points
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Pressure Points
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 7 + A damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 9 + A damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 7 + A damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 9 + A damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: You strike at key nerve clusters to leave your foe staggered.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: You strike at key nerve clusters to leave your foe staggered.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Pressure Points
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; A < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 7 + A damage; A < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 9 + A damage; A < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Pressure Points
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
