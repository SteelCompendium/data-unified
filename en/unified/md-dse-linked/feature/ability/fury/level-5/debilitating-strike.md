---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: While [slowed](../../../../condition/slowed.md) this way, the target takes 1 damage for every square they move, including from [forced movement](../../../../movement/forced-movement.md).
feature_type: ability
file_basename: debilitating-strike
file_dpath: feature/ability/fury/level-5
flavor: You need just one blow to sabotage your target.
item_id: debilitating-strike
item_name: Debilitating Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Debilitating Strike
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/debilitating-strike
source: mcdm.heroes.v1
target: One creature
tier1: 10 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 14 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 20 + M damage; M < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: While [slowed](../../../../condition/slowed.md) this way, the target takes 1 damage for every square they move, including from [forced movement](../../../../movement/forced-movement.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 10 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 14 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 20 + M damage; M < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You need just one blow to sabotage your target.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: While [slowed](../../../../condition/slowed.md) this way, the target takes 1 damage for every square they move, including from [forced movement](../../../../movement/forced-movement.md).
    flavor: You need just one blow to sabotage your target.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Debilitating Strike
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/debilitating-strike
    target: One creature
    tier1: 10 + M damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 14 + M damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 20 + M damage; M < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Debilitating Strike
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
