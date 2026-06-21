---
action_type: feature
class: elementalist
feature_type: feature
file_basename: breath
file_dpath: feature/elementalist/level-10
item_id: breath
item_name: Breath
level: "10"
name: Breath
scc: mcdm.heroes.v1/feature.elementalist.level-10/breath
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You have an epic resource called breath. Each time you finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite), you gain breath equal to the [XP](scc.v1:mcdm.heroes.v1/rule.resource/experience) you gain. You can spend any number of breath to gain essence (no action required). When you do, 1 breath becomes 3 essence.

        Breath remains until you convert it to essence.
feature_type: feature
metadata:
    class: elementalist
    level: "10"
    name: Breath
    scc: mcdm.heroes.v1/feature.elementalist.level-10/breath
    type: feature
name: Breath
type: feature
```
