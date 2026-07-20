---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
feature_type: ability
file_basename: staggering-blow
file_dpath: feature/ability/shadow/level-3
flavor: There's no recovering from this.
item_id: staggering-blow
item_name: Staggering Blow
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Staggering Blow
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
source: mcdm.heroes.v1
target: One creature
tier1: 7 + A damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 11 + A damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
tier3: 16 + A damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 7 + A damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 11 + A damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
      tier3: 16 + A damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
flavor: There's no recovering from this.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 7 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    flavor: There's no recovering from this.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "3"
    name: Staggering Blow
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
    target: One creature
    tier1: 7 + A damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 11 + A damage; M < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    tier3: 16 + A damage; M < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    type: ability
name: Staggering Blow
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
