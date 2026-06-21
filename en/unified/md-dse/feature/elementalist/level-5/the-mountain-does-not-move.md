---
action_type: feature
class: elementalist
feature_type: feature
file_basename: the-mountain-does-not-move
file_dpath: feature/elementalist/level-5
item_id: the-mountain-does-not-move
item_name: The Mountain Does Not Move
level: "5"
name: The Mountain Does Not Move
scc: mcdm.heroes.v1/feature.elementalist.level-5/the-mountain-does-not-move
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You stand firm and magnetize your allies to stay grounded. Your [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) increases by your level.

        Additionally, whenever an ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of your [Hurl Element](scc.v1:mcdm.heroes.v1/feature.ability.elementalist.level-1/hurl-element) ability is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to decrease your [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) down to a minimum of 0, then increase the ally's [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) by an amount equal to the [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) you lost. This change lasts until the end of the round.
feature_type: feature
metadata:
    class: elementalist
    level: "5"
    name: The Mountain Does Not Move
    scc: mcdm.heroes.v1/feature.elementalist.level-5/the-mountain-does-not-move
    type: feature
name: The Mountain Does Not Move
type: feature
```
