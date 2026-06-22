---
action_type: Main action
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: The target is marked by you.
feature_type: ability
file_basename: that-one-is-mine
file_dpath: feature/ability/tactician/level-9
flavor: You focus on making an enemy irrelevant.
item_id: that-one-is-mine
item_name: That One Is Mine!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: That One Is Mine!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-9/that-one-is-mine
source: mcdm.heroes.v1
subclass: vanguard
target: One creature
tier1: 8 + M damage
tier2: 13 + M damage
tier3: 17 + M damage
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: The target is marked by you.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M damage
      tier2: 13 + M damage
      tier3: 17 + M damage
feature_type: ability
flavor: You focus on making an enemy irrelevant.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 11 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: The target is marked by you.
    flavor: You focus on making an enemy irrelevant.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: That One Is Mine!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-9/that-one-is-mine
    subclass: vanguard
    target: One creature
    tier1: 8 + M damage
    tier2: 13 + M damage
    tier3: 17 + M damage
    type: ability
name: That One Is Mine!
target: One creature
type: feature
usage: Main action
```
