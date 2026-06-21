---
action_type: feature
class: tactician
feature_type: feature
file_basename: melee-superiority
file_dpath: feature/tactician/level-2
item_id: melee-superiority
item_name: Melee Superiority
level: "2"
name: Melee Superiority
scc: mcdm.heroes.v1/feature.tactician.level-2/melee-superiority
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        After constant drills, you can more accurately anticipate an enemy's plan and thwart their attempts to move across the battlefield. Whenever you make an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack), the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced to 0 until the end of the current [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).

        **Mark Benefit:** When a creature marked by you attempts to move or [shift](scc.v1:mcdm.heroes.v1/movement/shifting) within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of your [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) and spend 2 focus to make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that creature.
feature_type: feature
metadata:
    class: tactician
    level: "2"
    name: Melee Superiority
    scc: mcdm.heroes.v1/feature.tactician.level-2/melee-superiority
    type: feature
name: Melee Superiority
type: feature
```
