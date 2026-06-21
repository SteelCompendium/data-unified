---
action_type: Main action
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: When you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target, you can move into any square they leave. If you take damage from an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving this way, the target takes the same damage.
feature_type: ability
file_basename: out-of-the-way
file_dpath: feature/ability/fury/level-1
flavor: Your enemies will clear your path—whether they want to or not.
item_id: out-of-the-way
item_name: Out of the Way!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Out of the Way!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/out-of-the-way
source: mcdm.heroes.v1
target: One creature
tier1: 3 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 5 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 8 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: When you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target, you can move into any square they leave. If you take damage from an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving this way, the target takes the same damage.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier2: 5 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 8 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
feature_type: ability
flavor: Your enemies will clear your path—whether they want to or not.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 3 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: When you [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target, you can move into any square they leave. If you take damage from an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving this way, the target takes the same damage.
    flavor: Your enemies will clear your path—whether they want to or not.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Out of the Way!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/out-of-the-way
    target: One creature
    tier1: 3 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier2: 5 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 8 + M damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Out of the Way!
target: One creature
type: feature
usage: Main action
```
