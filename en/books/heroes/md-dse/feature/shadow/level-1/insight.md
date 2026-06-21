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
        By observing your enemy, you learn how to use their weaknesses against them, building up a [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) called insight.

        ##### Insight in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) (as determined by the Director), you gain insight equal to your [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories). At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) during combat, you gain 1d3 insight.

        Additionally, the first time each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) that you deal damage incorporating 1 or more [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), you gain 1 insight.

        Whenever you use a [heroic ability](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) that makes use of a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), that ability costs 1 fewer insight if you have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) or double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on it. If the ability has multiple targets, the cost is reduced even if the ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) or has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against only one target.

        You lose any remaining insight at the end of the encounter.

        ##### Insight Outside of Combat

        Although you can't gain insight outside of combat, you can use your [heroic abilities](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) and effects that cost insight without spending it. Whenever you use an ability or effect outside of combat that costs insight, you can't use that same ability or effect outside of combat again until you earn 1 or more [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories) or finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite).

        When you use an ability outside of combat that lets you spend unlimited insight on its effect, such as [Black Ash Teleport](scc.v1:mcdm.heroes.v1/feature.ability.shadow.level-1/black-ash-teleport), you can use it as if you had spent an amount of insight equal to your [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories).
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
