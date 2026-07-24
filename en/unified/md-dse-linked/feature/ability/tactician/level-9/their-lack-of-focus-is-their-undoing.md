---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Each target uses a [signature ability](../../../../rule/combat/signature-ability.md) against one or more targets of your choosing, with each ability automatically obtaining a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md). After resolving the targets' abilities, you make a [power roll](../../../../rule/dice/power-roll.md) against each original target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: R < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: R < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: R < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
file_basename: their-lack-of-focus-is-their-undoing
file_dpath: feature/ability/tactician/level-9
flavor: You trick your enemies into attacking each other and leave them confused by the aftermath.
item_id: their-lack-of-focus-is-their-undoing
item_name: Their Lack of Focus Is Their Undoing
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Weapon
level: "9"
name: Their Lack of Focus Is Their Undoing
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-9/their-lack-of-focus-is-their-undoing
source: mcdm.heroes.v1
subclass: insurgent
target: Three enemies
tier1: R < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: R < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: R < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Each target uses a [signature ability](../../../../rule/combat/signature-ability.md) against one or more targets of your choosing, with each ability automatically obtaining a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md). After resolving the targets' abilities, you make a [power roll](../../../../rule/dice/power-roll.md) against each original target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: R < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: R < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: R < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You trick your enemies into attacking each other and leave them confused by the aftermath.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 11 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: Each target uses a [signature ability](../../../../rule/combat/signature-ability.md) against one or more targets of your choosing, with each ability automatically obtaining a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md). After resolving the targets' abilities, you make a [power roll](../../../../rule/dice/power-roll.md) against each original target.
          name: Effect
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: R < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
          tier2: R < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
          tier3: R < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    flavor: You trick your enemies into attacking each other and leave them confused by the aftermath.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Weapon
    level: "9"
    name: Their Lack of Focus Is Their Undoing
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-9/their-lack-of-focus-is-their-undoing
    subclass: insurgent
    target: Three enemies
    tier1: R < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: R < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: R < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Their Lack of Focus Is Their Undoing
target: Three enemies
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
