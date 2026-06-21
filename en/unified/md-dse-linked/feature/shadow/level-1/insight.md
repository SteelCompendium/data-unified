---
action_type: feature
class: shadow
feature_type: feature
file_basename: insight
file_dpath: feature/shadow/level-1
item_id: insight
item_name: Insight
level: "1"
name: Insight
scc: mcdm.heroes.v1/feature.shadow.level-1/insight
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        By observing your enemy, you learn how to use their weaknesses against them, building up a [Heroic Resource](../../../rule/resource/heroic-resource.md) called insight.

        ##### Insight in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](../../../rule/combat/combat-round.md) (as determined by the Director), you gain insight equal to your [Victories](../../../rule/resource/victories.md). At the start of each of your [turns](../../../rule/combat/turn.md) during combat, you gain 1d3 insight.

        Additionally, the first time each [combat round](../../../rule/combat/combat-round.md) that you deal damage incorporating 1 or more [surges](../../../rule/resource/surge.md), you gain 1 insight.

        Whenever you use a [heroic ability](../../../rule/general/heroic-ability.md) that makes use of a [power roll](../../../rule/dice/power-roll.md), that ability costs 1 fewer insight if you have an [edge](../../../rule/dice/edge.md) or double [edge](../../../rule/dice/edge.md) on it. If the ability has multiple targets, the cost is reduced even if the ability gains an [edge](../../../rule/dice/edge.md) or has a double [edge](../../../rule/dice/edge.md) against only one target.

        You lose any remaining insight at the end of the encounter.

        ##### Insight Outside of Combat

        Although you can't gain insight outside of combat, you can use your [heroic abilities](../../../rule/general/heroic-ability.md) and effects that cost insight without spending it. Whenever you use an ability or effect outside of combat that costs insight, you can't use that same ability or effect outside of combat again until you earn 1 or more [Victories](../../../rule/resource/victories.md) or finish a [respite](../../../rule/resource/respite.md).

        When you use an ability outside of combat that lets you spend unlimited insight on its effect, such as [Black Ash Teleport](../../ability/shadow/level-1/black-ash-teleport.md), you can use it as if you had spent an amount of insight equal to your [Victories](../../../rule/resource/victories.md).
feature_type: feature
metadata:
    class: shadow
    level: "1"
    name: Insight
    scc: mcdm.heroes.v1/feature.shadow.level-1/insight
    type: feature
name: Insight
type: feature
```
