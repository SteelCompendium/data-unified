---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: fury
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can select a new target of the same [size](../../../../rule/character/size.md) or smaller within [distance](../../../../rule/combat/distance.md) to be force moved instead. You become the source of the [forced movement](../../../../movement/forced-movement.md), determine the new target's destination, and can [push](../../../../movement/forced-movement.md) the target instead of using the original [forced movement](../../../../movement/forced-movement.md) type. Additionally, the [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to your [Might](../../../../rule/character/might.md) score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to twice your [Might](../../../../rule/character/might.md) score instead.
feature_type: ability
file_basename: lines-of-force
file_dpath: feature/ability/fury/level-1
flavor: You redirect the energy of motion.
item_id: lines-of-force
item_name: Lines of Force
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
level: "1"
name: Lines of Force
scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
source: mcdm.heroes.v1
subclass: berserker
subtype: triggered
target: Self or one creature
trigger: The target would be [force moved](../../../../movement/forced-movement.md).
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: You can select a new target of the same [size](../../../../rule/character/size.md) or smaller within [distance](../../../../rule/combat/distance.md) to be force moved instead. You become the source of the [forced movement](../../../../movement/forced-movement.md), determine the new target's destination, and can [push](../../../../movement/forced-movement.md) the target instead of using the original [forced movement](../../../../movement/forced-movement.md) type. Additionally, the [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to your [Might](../../../../rule/character/might.md) score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to twice your [Might](../../../../rule/character/might.md) score instead.
feature_type: ability
flavor: You redirect the energy of motion.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: fury
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - effect: You can select a new target of the same [size](../../../../rule/character/size.md) or smaller within [distance](../../../../rule/combat/distance.md) to be force moved instead. You become the source of the [forced movement](../../../../movement/forced-movement.md), determine the new target's destination, and can [push](../../../../movement/forced-movement.md) the target instead of using the original [forced movement](../../../../movement/forced-movement.md) type. Additionally, the [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to your [Might](../../../../rule/character/might.md) score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: The [forced movement](../../../../movement/forced-movement.md) [distance](../../../../rule/combat/distance.md) gains a [bonus](../../../../rule/dice/bonuses-and-penalties.md) equal to twice your [Might](../../../../rule/character/might.md) score instead.
    flavor: You redirect the energy of motion.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
    level: "1"
    name: Lines of Force
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
    subclass: berserker
    subtype: triggered
    target: Self or one creature
    trigger: The target would be [force moved](../../../../movement/forced-movement.md).
    type: ability
name: Lines of Force
target: Self or one creature
trigger: The target would be [force moved](../../../../movement/forced-movement.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
