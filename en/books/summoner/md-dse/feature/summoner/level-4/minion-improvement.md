---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: minion-improvement
file_dpath: feature/summoner/level-4
item_id: minion-improvement
item_name: Minion Improvement
level: "4"
name: Minion Improvement
scc: mcdm.summoner.v1/feature.summoner.level-4/minion-improvement
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Your maximum number of [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) increases by 4.

        You can increase each of your [minions'](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) as shown on the 4th-Level Minion Stamina Increase table. Additionally, each [minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) that receives a [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) boost can treat their [characteristics](scc.v1:mcdm.heroes.v1/rule.character/characteristic) as one higher for the purposes of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency) (to a maximum value of 3).

        These benefits are not reflected in the stat blocks of new [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) you acquire.

        ###### 4th-Level Minion Stamina Increase

        | Minion | Stamina Increase |
        |--------|-----------------|
        | Signature Minion | Stamina +1 |
        | 3-Essence Minion | Stamina +3 |
        | 5-Essence Minion | Stamina +2 |
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "4"
    name: Minion Improvement
    scc: mcdm.summoner.v1/feature.summoner.level-4/minion-improvement
    type: feature
name: Minion Improvement
type: feature
```
