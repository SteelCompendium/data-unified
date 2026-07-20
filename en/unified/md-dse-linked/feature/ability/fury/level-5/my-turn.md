---
action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: You can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: my-turn
file_dpath: feature/ability/fury/level-5
flavor: You quickly strike back at a foe.
item_id: my-turn
item_name: My Turn!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: My Turn!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
source: mcdm.heroes.v1
subtype: triggered
target: The triggering creature
tier1: 6 + M damage
tier2: 9 + M damage
tier3: 13 + M damage
trigger: A creature causes you to be [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md), or damages you while you are [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md).
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can spend a [Recovery](../../../../rule/health/recoveries.md).
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 6 + M damage
      tier2: 9 + M damage
      tier3: 13 + M damage
feature_type: ability
flavor: You quickly strike back at a foe.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: You can spend a [Recovery](../../../../rule/health/recoveries.md).
    flavor: You quickly strike back at a foe.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: My Turn!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
    subtype: triggered
    target: The triggering creature
    tier1: 6 + M damage
    tier2: 9 + M damage
    tier3: 13 + M damage
    trigger: A creature causes you to be [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md), or damages you while you are [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md).
    type: ability
name: My Turn!
target: The triggering creature
trigger: A creature causes you to be [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md), or damages you while you are [winded](../../../../rule/health/winded.md) or [dying](../../../../rule/health/dying.md).
type: feature
usage: Free [triggered](../../../../rule/combat/triggered-action.md)
```
