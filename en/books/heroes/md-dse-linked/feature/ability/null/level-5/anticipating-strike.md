---
action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: This [strike](../../../../rule/combat/strike.md) resolves before the triggering movement or main action.
feature_type: ability
file_basename: anticipating-strike
file_dpath: feature/ability/null/level-5
flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
item_id: anticipating-strike
item_name: Anticipating Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Anticipating Strike
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/anticipating-strike
source: mcdm.heroes.v1
subtype: triggered
target: One creature
tier1: 7 + A damage; I < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
tier2: 10 + A damage; I < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
tier3: 13 + A damage; I < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
trigger: The target moves or uses a main action.
type: ability
---

```ds-feature
cost: 9 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: This [strike](../../../../rule/combat/strike.md) resolves before the triggering movement or main action.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 7 + A damage; I < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
      tier2: 10 + A damage; I < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
      tier3: 13 + A damage; I < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
feature_type: ability
flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
    class: "null"
    cost: 9 Discipline
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: This [strike](../../../../rule/combat/strike.md) resolves before the triggering movement or main action.
    flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Anticipating Strike
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-5/anticipating-strike
    subtype: triggered
    target: One creature
    tier1: 7 + A damage; I < WEAK, [restrained](../../../../condition/restrained.md) (save ends)
    tier2: 10 + A damage; I < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)
    tier3: 13 + A damage; I < STRONG, [restrained](../../../../condition/restrained.md) (save ends)
    trigger: The target moves or uses a main action.
    type: ability
name: Anticipating Strike
target: One creature
trigger: The target moves or uses a main action.
type: feature
usage: Free [triggered](../../../../rule/combat/triggered-action.md)
```
