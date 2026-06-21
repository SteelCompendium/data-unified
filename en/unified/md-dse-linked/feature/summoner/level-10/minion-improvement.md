---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: minion-improvement
file_dpath: feature/summoner/level-10
item_id: minion-improvement
item_name: Minion Improvement
level: "10"
name: Minion Improvement
scc: mcdm.summoner.v1/feature.summoner.level-10/minion-improvement
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You now start encounters and round-tracked situations by summoning up to two additional minions for every two [Victories](../../../rule/resource/victories.md) you have (in addition to the two you normally summon).

        Each of your minions' [Stamina](../../../rule/health/stamina.md) improves as shown on the 10th-Level Minion Stamina Increase table. Additionally, each minion that receives a [Stamina](../../../rule/health/stamina.md) boost can treat their [characteristics](../../../rule/character/characteristic.md) as one higher for the purposes of resisting [potencies](../../../rule/character/potency.md) (to a maximum value of 5).

        ###### 10th-Level Minion Stamina Increase

        | Minion | Stamina Increase |
        |--------|-----------------|
        | Signature Minion | Stamina +1 (to a total of +3) |
        | 3-Essence Minion | Stamina +3 (to a total of +9) |
        | 5-Essence Minion | Stamina +2 (to a total of +6) |
        | 7-Essence Minion | Stamina +5 (to a total of +10) |
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "10"
    name: Minion Improvement
    scc: mcdm.summoner.v1/feature.summoner.level-10/minion-improvement
    type: feature
name: Minion Improvement
type: feature
```
