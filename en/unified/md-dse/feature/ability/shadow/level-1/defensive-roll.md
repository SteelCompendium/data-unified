---
action_type: Triggered
class: shadow
distance: Self
effect: You take half the triggering damage, then can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares after the triggering effect resolves. If you end this [shift](scc.v1:mcdm.heroes.v1/movement/shifting) with [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover), you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed.
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
spend: '1 Insight: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any effects associated with the damage are reduced by 1 for you.'
subclass: caustic-alchemy
subtype: triggered
target: Self
trigger: Another creature damages you.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the triggering damage, then can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares after the triggering effect resolves. If you end this [shift](scc.v1:mcdm.heroes.v1/movement/shifting) with [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover), you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed.
    - effect: '1 Insight: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any effects associated with the damage are reduced by 1 for you.'
      name: Spend
feature_type: ability
flavor: When an enemy attacks, you roll with the impact to reduce the harm.
keywords: []
metadata:
    action_type: Triggered
    class: shadow
    distance: Self
    effect: You take half the triggering damage, then can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares after the triggering effect resolves. If you end this [shift](scc.v1:mcdm.heroes.v1/movement/shifting) with [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment) or [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover), you can use the [Hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) maneuver even if you are observed.
    flavor: When an enemy attacks, you roll with the impact to reduce the harm.
    keywords: []
    level: "1"
    name: Defensive Roll
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/defensive-roll
    spend: '1 Insight: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any effects associated with the damage are reduced by 1 for you.'
    subclass: caustic-alchemy
    subtype: triggered
    target: Self
    trigger: Another creature damages you.
    type: ability
name: Defensive Roll
target: Self
trigger: Another creature damages you.
type: feature
usage: Triggered
```
