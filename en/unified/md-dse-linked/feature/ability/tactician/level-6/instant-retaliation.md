---
action_type: Free triggered
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: The target takes half the damage. You then make a [power roll](../../../../rule/dice/power-roll.md) against the triggering creature.
feature_type: ability
file_basename: instant-retaliation
file_dpath: feature/ability/tactician/level-6
flavor: You [parry](../level-1/parry.md) with almost [supernatural](../../../../rule/general/supernatural.md) [speed](../../../../rule/character/speed.md).
item_id: instant-retaliation
item_name: Instant Retaliation
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "6"
name: Instant Retaliation
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
source: mcdm.heroes.v1
subtype: triggered
target: One ally
tier1: A < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: A < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: A < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: The target takes half the damage. You then make a [power roll](../../../../rule/dice/power-roll.md) against the triggering creature.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: A < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: A < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: A < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You [parry](../level-1/parry.md) with almost [supernatural](../../../../rule/general/supernatural.md) [speed](../../../../rule/character/speed.md).
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Free triggered
    class: tactician
    cost: 9 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: The target takes half the damage. You then make a [power roll](../../../../rule/dice/power-roll.md) against the triggering creature.
    flavor: You [parry](../level-1/parry.md) with almost [supernatural](../../../../rule/general/supernatural.md) [speed](../../../../rule/character/speed.md).
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "6"
    name: Instant Retaliation
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
    subtype: triggered
    target: One ally
    tier1: A < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: A < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: A < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    trigger: A creature deals damage to the target.
    type: ability
name: Instant Retaliation
target: One ally
trigger: A creature deals damage to the target.
type: feature
usage: Free triggered
```
