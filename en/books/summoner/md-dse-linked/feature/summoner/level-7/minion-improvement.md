---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: minion-improvement
file_dpath: feature/summoner/level-7
item_id: minion-improvement
item_name: Minion Improvement
level: "7"
name: Minion Improvement
scc: mcdm.summoner.v1/feature.summoner.level-7/minion-improvement
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        At the start of each of your [turns](../../../rule/combat/turn.md) during combat, you can summon one additional signature minion at no cost into an unoccupied space within your Summoner's Range (no action required).

        Additionally, you can increase each of your minions' [Stamina](../../../rule/health/stamina.md) as shown on the 7th-Level Minion Stamina Increase table. Additionally, each minion that receives a [Stamina](../../../rule/health/stamina.md) boost can treat their [characteristics](../../../rule/character/characteristic.md) as one higher for the purposes of resisting [potencies](../../../rule/character/potency.md) (to a maximum value of 4).

        These benefits are not reflected in the stat blocks of new minions you acquire.

        ###### 7th-Level Minion Stamina Increase

        | Minion | Stamina Increase |
        |--------|-----------------|
        | Signature Minion | Stamina +1 (to a total of +2) |
        | 3-Essence Minion | Stamina +3 (to a total of +6) |
        | 5-Essence Minion | Stamina +2 (to a total of +4) |
        | 7-Essence Minion | Stamina +5 |
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "7"
    name: Minion Improvement
    scc: mcdm.summoner.v1/feature.summoner.level-7/minion-improvement
    type: feature
name: Minion Improvement
type: feature
```
