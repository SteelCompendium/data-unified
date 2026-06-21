---
action_type: feature
class: summoner
feature_source: circle
feature_type: feature
file_basename: portfolio-champion
file_dpath: feature/summoner/level-8
item_id: portfolio-champion
item_name: Portfolio Champion
level: "8"
name: Portfolio Champion
scc: mcdm.summoner.v1/feature.summoner.level-8/portfolio-champion
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Your circle now allows you to add a champion to your portfolio. Champions follow the same rules as your other minions, with the following exceptions:

        - You can only summon and command one instance of your champion.
        - Your champion is in their own squad that does not count toward your maximum number of squads.
        - Your champion can regain [Stamina](../../../rule/health/stamina.md) and gain [temporary Stamina](../../../rule/health/temporary-stamina.md).
        - Your champion uses your [Recoveries](../../../rule/health/recoveries.md) to regain [Stamina](../../../rule/health/stamina.md).
        - Your champion can take the [Heal](../../common/main-actions/heal.md) and [Defend](../../common/main-actions/defend.md) Actions.
        - Your champion uses the normal rules for maneuvers.
        - You have an [edge](../../../rule/dice/edge.md) whenever you use an ability with the Champion keyword from your Champion's space.
        - Your champion refuses to be referred to as a minion.

        After summoning a champion, you can't summon them again until you earn a [Victory](../../../rule/resource/victories.md).

        Your champion gains additional features at 10th level. This includes a special Champion Action ability that costs eidos to use (see [Eidos](../level-10/eidos.md)). This ability can be activated once per encounter at the end of any other creature's [turn](../../../rule/combat/turn.md).
feature_type: feature
metadata:
    class: summoner
    feature_source: circle
    level: "8"
    name: Portfolio Champion
    scc: mcdm.summoner.v1/feature.summoner.level-8/portfolio-champion
    type: feature
name: Portfolio Champion
type: feature
```
