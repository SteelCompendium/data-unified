---
action_type: Main action
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: While [grabbed](../../../../condition/grabbed.md) this way, the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../common/maneuvers/escape-grab.md) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](../../../../rule/character/agility.md) score.
feature_type: ability
file_basename: iron-grip
file_dpath: feature/ability/null/level-5
flavor: You grab the target with [supernatural](../../../../rule/general/supernatural.md) force.
item_id: iron-grip
item_name: Iron Grip
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Iron Grip
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
source: mcdm.heroes.v1
target: One creature
tier1: 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
tier2: 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
tier3: 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)
type: ability
---

```ds-feature
cost: 9 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: While [grabbed](../../../../condition/grabbed.md) this way, the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../common/maneuvers/escape-grab.md) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](../../../../rule/character/agility.md) score.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
      tier2: 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
      tier3: 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)
feature_type: ability
flavor: You grab the target with [supernatural](../../../../rule/general/supernatural.md) force.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 9 Discipline
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: While [grabbed](../../../../condition/grabbed.md) this way, the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../common/maneuvers/escape-grab.md) maneuver. Each time they use that maneuver, they take damage equal to twice your [Agility](../../../../rule/character/agility.md) score.
    flavor: You grab the target with [supernatural](../../../../rule/general/supernatural.md) force.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Iron Grip
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
    target: One creature
    tier1: 10 + A damage; A < WEAK, [grabbed](../../../../condition/grabbed.md)
    tier2: 14 + A damage; A < AVERAGE, [grabbed](../../../../condition/grabbed.md)
    tier3: 18 + A damage; A < STRONG, [grabbed](../../../../condition/grabbed.md)
    type: ability
name: Iron Grip
target: One creature
type: feature
usage: Main action
```
