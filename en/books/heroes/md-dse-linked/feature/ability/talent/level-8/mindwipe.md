---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effect: The target can't communicate with anyone until the end of the encounter.
feature_type: ability
file_basename: mindwipe
file_dpath: feature/ability/talent/level-8
flavor: You attempt to make them forget all their training.
item_id: mindwipe
item_name: Mindwipe
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
level: "8"
name: Mindwipe
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-8/mindwipe
source: mcdm.heroes.v1
target: One creature
tier1: 12 + R damage; R < WEAK, the target takes a [bane](../../../../rule/dice/bane.md) on their next [power roll](../../../../rule/dice/power-roll.md)
tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
tier3: 23 + R damage; R < STRONG, the target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effects:
    - effect: The target can't communicate with anyone until the end of the encounter.
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 12 + R damage; R < WEAK, the target takes a [bane](../../../../rule/dice/bane.md) on their next [power roll](../../../../rule/dice/power-roll.md)
      tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
      tier3: 23 + R damage; R < STRONG, the target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
feature_type: ability
flavor: You attempt to make them forget all their training.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: '[Melee](../../../../rule/combat/melee.md) 2'
    effect: The target can't communicate with anyone until the end of the encounter.
    flavor: You attempt to make them forget all their training.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Psionic
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telepathy
    level: "8"
    name: Mindwipe
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/mindwipe
    target: One creature
    tier1: 12 + R damage; R < WEAK, the target takes a [bane](../../../../rule/dice/bane.md) on their next [power roll](../../../../rule/dice/power-roll.md)
    tier2: 17 + R damage; R < AVERAGE, the target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
    tier3: 23 + R damage; R < STRONG, the target has a double [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) (save ends)
    type: ability
name: Mindwipe
target: One creature
type: feature
usage: Main action
```
