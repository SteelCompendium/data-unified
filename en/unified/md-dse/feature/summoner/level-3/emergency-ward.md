---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: emergency-ward
file_dpath: feature/summoner/level-3
item_id: emergency-ward
item_name: Emergency Ward
level: "3"
name: Emergency Ward
scc: mcdm.summoner.v1/feature.summoner.level-3/emergency-ward
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: The first time each [round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) you take [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage), you can use a [free triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 after the triggering effect resolves and summon a signature [minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) into the square you left (as long as there is enough space).
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "3"
    name: Emergency Ward
    scc: mcdm.summoner.v1/feature.summoner.level-3/emergency-ward
    type: feature
name: Emergency Ward
type: feature
```
