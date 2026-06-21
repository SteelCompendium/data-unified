---
action_type: Main action
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
feature_type: ability
file_basename: eviscerate
file_dpath: feature/ability/shadow/level-1
flavor: You leave your foe bleeding out after a devastating attack.
item_id: eviscerate
item_name: Eviscerate
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Eviscerate
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
source: mcdm.heroes.v1
target: One creature
tier1: 4 + A damage; A < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 6 + A damage; A < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 10 + A damage; A < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 3 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; A < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 6 + A damage; A < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 10 + A damage; A < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
feature_type: ability
flavor: You leave your foe bleeding out after a devastating attack.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 3 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    flavor: You leave your foe bleeding out after a devastating attack.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Eviscerate
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
    target: One creature
    tier1: 4 + A damage; A < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier2: 6 + A damage; A < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier3: 10 + A damage; A < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Eviscerate
target: One creature
type: feature
usage: Main action
```
