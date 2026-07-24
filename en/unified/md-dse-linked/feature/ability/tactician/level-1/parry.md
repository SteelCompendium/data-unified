---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: tactician
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effects:
    - effect: You can [shift](../../../../movement/shifting.md) 1 square. If the target is you, or if you end this [shift](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to the target, the target takes half the damage. If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is decreased by 1.
      name: Effect
    - cost: Spend 1 Focus
      effect: This ability's [distance](../../../../rule/combat/distance.md) becomes [Melee](../../../../rule/combat/melee.md) 1 + your [Reason](../../../../rule/character/reason.md) score, and you can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score instead of 1 square.
feature_type: ability
file_basename: parry
file_dpath: feature/ability/tactician/level-1
flavor: Your quick reflexes cost an enemy the precision they seek.
item_id: parry
item_name: Parry
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "1"
name: Parry
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
source: mcdm.heroes.v1
subclass: vanguard
subtype: triggered
target: Self or one ally
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effects:
    - effect: You can [shift](../../../../movement/shifting.md) 1 square. If the target is you, or if you end this [shift](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to the target, the target takes half the damage. If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is decreased by 1.
      name: Effect
    - cost: Spend 1 Focus
      effect: This ability's [distance](../../../../rule/combat/distance.md) becomes [Melee](../../../../rule/combat/melee.md) 1 + your [Reason](../../../../rule/character/reason.md) score, and you can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score instead of 1 square.
feature_type: ability
flavor: Your quick reflexes cost an enemy the precision they seek.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: tactician
    distance: '[Melee](../../../../rule/combat/melee.md) 2'
    effects:
        - effect: You can [shift](../../../../movement/shifting.md) 1 square. If the target is you, or if you end this [shift](../../../../movement/shifting.md) [adjacent](../../../../rule/combat/adjacent.md) to the target, the target takes half the damage. If the damage has any [potency](../../../../rule/character/potency.md) effect associated with it, the [potency](../../../../rule/character/potency.md) is decreased by 1.
          name: Effect
        - cost: Spend 1 Focus
          effect: This ability's [distance](../../../../rule/combat/distance.md) becomes [Melee](../../../../rule/combat/melee.md) 1 + your [Reason](../../../../rule/character/reason.md) score, and you can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Reason](../../../../rule/character/reason.md) score instead of 1 square.
    flavor: Your quick reflexes cost an enemy the precision they seek.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "1"
    name: Parry
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
    subclass: vanguard
    subtype: triggered
    target: Self or one ally
    trigger: A creature deals damage to the target.
    type: ability
name: Parry
target: Self or one ally
trigger: A creature deals damage to the target.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
