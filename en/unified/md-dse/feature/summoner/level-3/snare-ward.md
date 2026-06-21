---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: snare-ward
file_dpath: feature/summoner/level-3
item_id: snare-ward
item_name: Snare Ward
level: "3"
name: Snare Ward
scc: mcdm.summoner.v1/feature.summoner.level-3/snare-ward
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: Whenever an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature deals [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to you, you can use a [free triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to pull that creature toward one of your [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) within your Summoner's Range a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "3"
    name: Snare Ward
    scc: mcdm.summoner.v1/feature.summoner.level-3/snare-ward
    type: feature
name: Snare Ward
type: feature
```
