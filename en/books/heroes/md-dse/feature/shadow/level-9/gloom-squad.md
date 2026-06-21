---
action_type: feature
class: shadow
feature_type: feature
file_basename: gloom-squad
file_dpath: feature/shadow/level-9
item_id: gloom-squad
item_name: Gloom Squad
level: "9"
name: Gloom Squad
scc: mcdm.heroes.v1/feature.shadow.level-9/gloom-squad
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can forgo gaining insight to create 1d6 clones of yourself in unoccupied [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) spaces. A clone acts on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) and uses your statistics, except they have 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). They are affected by any [conditions](scc.v1:mcdm.heroes.v1/rule.combat/condition) and effects on you, and last until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). A clone doesn't have insight and can't use the [Careful Observation](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-3/careful-observation) ability, the [Umbral Form](scc.v1:mcdm.heroes.v1/feature.shadow.level-6/umbral-form) feature, or any [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action). On their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), a clone has a move action, a maneuver, and a main action that they can use only to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). While making a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike), a clone must choose targets that you or another clone aren't also striking.

        Outside of combat, you can have one clone active for every 2 [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories) you have. If a clone is destroyed, you must wait 1 hour before creating another one.
feature_type: feature
metadata:
    class: shadow
    level: "9"
    name: Gloom Squad
    scc: mcdm.heroes.v1/feature.shadow.level-9/gloom-squad
    type: feature
name: Gloom Squad
type: feature
```
