---
action_type: Main action
class: "null"
cost: 3 Discipline
cost_amount: "3"
cost_resource: Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: stunning-blow
file_dpath: feature/ability/null/level-1
flavor: You focus your psionic technique into a concussive punch.
item_id: stunning-blow
item_name: Stunning Blow
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Stunning Blow
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + A damage; I < WEAK, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
tier2: 5 + A damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
tier3: 7 + A damage; I < STRONG, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 4 + A damage; I < WEAK, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 5 + A damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 7 + A damage; I < STRONG, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You focus your psionic technique into a concussive punch.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 3 Discipline
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You focus your psionic technique into a concussive punch.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Stunning Blow
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
    target: One creature or object
    tier1: 4 + A damage; I < WEAK, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 5 + A damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 7 + A damage; I < STRONG, [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Stunning Blow
target: One creature or object
type: feature
usage: Main action
```
