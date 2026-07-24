---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: elementalist
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target moves to trigger this ability, you can [teleport](../../../../movement/teleport.md) them at any point during the move.
      name: Effect
    - cost: Spend 1 Essence
      effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to twice your [Reason](../../../../rule/character/reason.md) score instead.
feature_type: ability
file_basename: subtle-relocation
file_dpath: feature/ability/elementalist/level-1
flavor: You call on the void to swallow and spit out an ally.
item_id: subtle-relocation
item_name: Subtle Relocation
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Void
level: "1"
name: Subtle Relocation
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/subtle-relocation
source: mcdm.heroes.v1
subclass: void
subtype: triggered
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target moves to trigger this ability, you can [teleport](../../../../movement/teleport.md) them at any point during the move.
      name: Effect
    - cost: Spend 1 Essence
      effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to twice your [Reason](../../../../rule/character/reason.md) score instead.
feature_type: ability
flavor: You call on the void to swallow and spit out an ally.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Void
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: elementalist
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score. If the target moves to trigger this ability, you can [teleport](../../../../movement/teleport.md) them at any point during the move.
          name: Effect
        - cost: Spend 1 Essence
          effect: You [teleport](../../../../movement/teleport.md) the target up to a number of squares equal to twice your [Reason](../../../../rule/character/reason.md) score instead.
    flavor: You call on the void to swallow and spit out an ally.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Void
    level: "1"
    name: Subtle Relocation
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/subtle-relocation
    subclass: void
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
    type: ability
name: Subtle Relocation
target: Self or one ally
trigger: The target starts their [turn](../../../../rule/combat/turn.md), moves, or is [force moved](../../../../movement/forced-movement.md).
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
