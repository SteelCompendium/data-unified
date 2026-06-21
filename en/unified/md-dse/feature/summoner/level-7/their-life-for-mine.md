---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: their-life-for-mine
file_dpath: feature/summoner/level-7
item_id: their-life-for-mine
item_name: Their Life for Mine
level: "7"
name: Their Life for Mine
scc: mcdm.summoner.v1/feature.summoner.level-7/their-life-for-mine
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        If you or an ally within your Summoner's Range would [die](scc.v1:mcdm.heroes.v1/rule.health/dying) from an effect that isn't age related, you sacrifice all your active minions (minimum 1) and spend all your essence (minimum 1) as a [free triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to bring the target back to life, reconstructing the damaged parts of their body with summoned material related to your portfolio. The target comes back with 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) plus 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) for each minion and essence used in the effect. You must have at least one fragment of the creature's remains, and the creature's soul must be willing to return to life for the effect to work.

        You can't use this feature again until you gain a new level, or until you spend 3 eidos to use it (see [Eidos](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/eidos)).
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "7"
    name: Their Life for Mine
    scc: mcdm.summoner.v1/feature.summoner.level-7/their-life-for-mine
    type: feature
name: Their Life for Mine
type: feature
```
