---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: tactician
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target gains 2 [surges](../../../../rule/resource/surge.md), which they can use on the triggering damage.
      name: Effect
    - cost: Spend 1 Focus
      effect: If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is increased by 1.
feature_type: ability
file_basename: advanced-tactics
file_dpath: feature/ability/tactician/level-1
flavor: Your leadership aids an ally.
item_id: advanced-tactics
item_name: Advanced Tactics
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Advanced Tactics
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/advanced-tactics
source: mcdm.heroes.v1
subclass: insurgent
subtype: triggered
target: One ally
trigger: The target deals damage to another creature.
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target gains 2 [surges](../../../../rule/resource/surge.md), which they can use on the triggering damage.
      name: Effect
    - cost: Spend 1 Focus
      effect: If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is increased by 1.
feature_type: ability
flavor: Your leadership aids an ally.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: tactician
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: The target gains 2 [surges](../../../../rule/resource/surge.md), which they can use on the triggering damage.
          name: Effect
        - cost: Spend 1 Focus
          effect: If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is increased by 1.
    flavor: Your leadership aids an ally.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Advanced Tactics
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/advanced-tactics
    subclass: insurgent
    subtype: triggered
    target: One ally
    trigger: The target deals damage to another creature.
    type: ability
name: Advanced Tactics
target: One ally
trigger: The target deals damage to another creature.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
