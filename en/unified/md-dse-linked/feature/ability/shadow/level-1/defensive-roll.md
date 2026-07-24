---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: shadow
distance: Self
effects:
    - effect: You take half the triggering damage, then can [shift](../../../../movement/shifting.md) up to 2 squares after the triggering effect resolves. If you end this [shift](../../../../movement/shifting.md) with [concealment](../../../../rule/combat/concealment.md) or [cover](../../../../rule/combat/cover.md), you can use the [Hide](../../../common/maneuvers/hide.md) maneuver even if you are observed.
      name: Effect
    - cost: Spend 1 Insight
      effect: The [potency](../../../../rule/character/potency.md) of any effects associated with the damage are reduced by 1 for you.
feature_type: ability
file_basename: defensive-roll
file_dpath: feature/ability/shadow/level-1
flavor: When an enemy attacks, you roll with the impact to reduce the harm.
item_id: defensive-roll
item_name: Defensive Roll
keywords: []
level: "1"
name: Defensive Roll
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/defensive-roll
source: mcdm.heroes.v1
subclass: caustic-alchemy
subtype: triggered
target: Self
trigger: Another creature damages you.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the triggering damage, then can [shift](../../../../movement/shifting.md) up to 2 squares after the triggering effect resolves. If you end this [shift](../../../../movement/shifting.md) with [concealment](../../../../rule/combat/concealment.md) or [cover](../../../../rule/combat/cover.md), you can use the [Hide](../../../common/maneuvers/hide.md) maneuver even if you are observed.
      name: Effect
    - cost: Spend 1 Insight
      effect: The [potency](../../../../rule/character/potency.md) of any effects associated with the damage are reduced by 1 for you.
feature_type: ability
flavor: When an enemy attacks, you roll with the impact to reduce the harm.
keywords: []
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: shadow
    distance: Self
    effects:
        - effect: You take half the triggering damage, then can [shift](../../../../movement/shifting.md) up to 2 squares after the triggering effect resolves. If you end this [shift](../../../../movement/shifting.md) with [concealment](../../../../rule/combat/concealment.md) or [cover](../../../../rule/combat/cover.md), you can use the [Hide](../../../common/maneuvers/hide.md) maneuver even if you are observed.
          name: Effect
        - cost: Spend 1 Insight
          effect: The [potency](../../../../rule/character/potency.md) of any effects associated with the damage are reduced by 1 for you.
    flavor: When an enemy attacks, you roll with the impact to reduce the harm.
    keywords: []
    level: "1"
    name: Defensive Roll
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/defensive-roll
    subclass: caustic-alchemy
    subtype: triggered
    target: Self
    trigger: Another creature damages you.
    type: ability
name: Defensive Roll
target: Self
trigger: Another creature damages you.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
