---
action_type: Maneuver
distance: Self
effect: You take a [bane](../../../rule/dice/bane.md) on this maneuver if your [size](../../../rule/character/size.md) is smaller than the size of the creature, object, or effect that has you [grabbed](../../../condition/grabbed.md).
feature_type: ability
file_basename: escape-grab
file_dpath: feature/ability/common
item_id: escape-grab
item_name: Escape Grab
keywords:
    - '-'
name: Escape Grab
power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.common/escape-grab
source: mcdm.heroes.v1
target: Self
tier1: No effect.
tier2: You can escape the grab, but if you do, a creature who has you [grabbed](../../../condition/grabbed.md) can make a [melee](../../../rule/combat/melee.md) [free strike](../../common/main-actions/free-strike.md) against you before you are no longer [grabbed](../../../condition/grabbed.md).
tier3: You are no longer [grabbed](../../../condition/grabbed.md).
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take a [bane](../../../rule/dice/bane.md) on this maneuver if your [size](../../../rule/character/size.md) is smaller than the size of the creature, object, or effect that has you [grabbed](../../../condition/grabbed.md).
    - roll: Power Roll + [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)
      tier1: No effect.
      tier2: You can escape the grab, but if you do, a creature who has you [grabbed](../../../condition/grabbed.md) can make a [melee](../../../rule/combat/melee.md) [free strike](../../common/main-actions/free-strike.md) against you before you are no longer [grabbed](../../../condition/grabbed.md).
      tier3: You are no longer [grabbed](../../../condition/grabbed.md).
feature_type: ability
keywords:
    - '-'
metadata:
    action_type: Maneuver
    distance: Self
    effect: You take a [bane](../../../rule/dice/bane.md) on this maneuver if your [size](../../../rule/character/size.md) is smaller than the size of the creature, object, or effect that has you [grabbed](../../../condition/grabbed.md).
    keywords:
        - '-'
    name: Escape Grab
    power_roll_characteristic: '[Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.common/escape-grab
    target: Self
    tier1: No effect.
    tier2: You can escape the grab, but if you do, a creature who has you [grabbed](../../../condition/grabbed.md) can make a [melee](../../../rule/combat/melee.md) [free strike](../../common/main-actions/free-strike.md) against you before you are no longer [grabbed](../../../condition/grabbed.md).
    tier3: You are no longer [grabbed](../../../condition/grabbed.md).
    type: ability
name: Escape Grab
target: Self
type: feature
usage: Maneuver
```
