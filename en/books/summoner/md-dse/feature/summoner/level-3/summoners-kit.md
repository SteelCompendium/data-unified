---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: summoners-kit
file_dpath: feature/summoner/level-3
item_id: summoners-kit
item_name: Summoner's Kit
level: "3"
name: Summoner's Kit
scc: mcdm.summoner.v1/feature.summoner.level-3/summoners-kit
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You conjure a kit for yourself. This kit includes an [implement](scc.v1:mcdm.heroes.v1/rule.treasure/implement), such as a rod or a baton, which grants you the following benefits:

        - The [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) of your [Summoner Strike](scc.v1:mcdm.summoner.v1/feature.ability.summoner.level-1/summoner-strike) ability increases to twice your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
        - The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of your [Summoner Strike](scc.v1:mcdm.summoner.v1/feature.ability.summoner.level-1/summoner-strike) ability increases to R < AVERAGE.
        - The distance of your [Summoner Strike](scc.v1:mcdm.summoner.v1/feature.ability.summoner.level-1/summoner-strike) ability is now equal to your Summoner's Range.

        Your kit also comes with wards like magic armor and transient [minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) forces. Choose one of the following wards.
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "3"
    name: Summoner's Kit
    scc: mcdm.summoner.v1/feature.summoner.level-3/summoners-kit
    type: feature
name: Summoner's Kit
type: feature
```
