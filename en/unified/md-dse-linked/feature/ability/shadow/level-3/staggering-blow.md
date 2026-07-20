---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: staggering-blow
file_dpath: feature/ability/shadow/level-3
flavor: There's no recovering from this.
item_id: staggering-blow
item_name: Staggering Blow
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "3"
name: Staggering Blow
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
source: mcdm.heroes.v1
target: One creature
tier1: 7 + A damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 11 + A damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
tier3: 16 + A damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 7 + A damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 11 + A damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
      tier3: 16 + A damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
feature_type: ability
flavor: There's no recovering from this.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: shadow
    cost: 7 Insight
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    flavor: There's no recovering from this.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "3"
    name: Staggering Blow
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
    target: One creature
    tier1: 7 + A damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 11 + A damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)
    tier3: 16 + A damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)
    type: ability
name: Staggering Blow
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
