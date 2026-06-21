---
action_type: Main action
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by a willing ally within 5 squares of you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: misdirecting-strike
file_dpath: feature/ability/shadow/level-3
flavor: '"Why are you looking at ME?!"'
item_id: misdirecting-strike
item_name: Misdirecting Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Misdirecting Strike
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/misdirecting-strike
source: mcdm.heroes.v1
target: One creature
tier1: 9 + A damage
tier2: 13 + A damage
tier3: 18 + A damage
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by a willing ally within 5 squares of you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 9 + A damage
      tier2: 13 + A damage
      tier3: 18 + A damage
feature_type: ability
flavor: '"Why are you looking at ME?!"'
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 7 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by a willing ally within 5 squares of you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: '"Why are you looking at ME?!"'
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "3"
    name: Misdirecting Strike
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/misdirecting-strike
    target: One creature
    tier1: 9 + A damage
    tier2: 13 + A damage
    tier3: 18 + A damage
    type: ability
name: Misdirecting Strike
target: One creature
type: feature
usage: Main action
```
