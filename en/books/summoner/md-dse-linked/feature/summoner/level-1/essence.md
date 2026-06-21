---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: essence
file_dpath: feature/summoner/level-1
item_id: essence
item_name: Essence
level: "1"
name: Essence
scc: mcdm.summoner.v1/feature.summoner.level-1/essence
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You and your minions have a unique reserve of essence as your [Heroic Resource](../../../rule/resource/heroic-resource.md). You use this magic to sculpt your forces and maintain control over the battlefield.

        #### Essence in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](../../../rule/combat/combat-round.md) (as determined by the Director), you gain essence equal to your [Victories](../../../rule/resource/victories.md).

        At the start of each of your [turns](../../../rule/combat/turn.md) during combat, you gain 2 essence.

        The first time each [round](../../../rule/combat/combat-round.md) that any minion (either yours or an enemy) dies unwillingly within your Summoner's Range, you gain 1 essence.

        Whenever you use a [heroic ability](../../../rule/general/heroic-ability.md) or call forth a minion that costs essence, you can willingly sacrifice one or more of your minions within your Summoner's Range to reduce the cost by 1. You can't kill minions this way if they used a [main action](../../../rule/combat/turn.md) or maneuver during the [turn](../../../rule/combat/turn.md). You can sacrifice more minions than you would reduce the cost by.

        You lose any remaining essence at the end of the encounter.

        #### Essence Outside of Combat

        Though you can't gain essence outside of combat, you can use your [heroic abilities](../../../rule/general/heroic-ability.md) and effects that cost essence without spending it. Whenever you use an ability or effect outside of combat that costs essence, you can't use that same ability or effect outside of combat again until you gain at least 1 [Victory](../../../rule/resource/victories.md) or finish a [respite](../../../rule/resource/respite.md).

        > **More Wielders of Quintessence**
        >
        > Essence is the "stuff of creation." Just as the elementalist uses essence to conjure fire, lightning, or warp space and time, the summoner uses essence to manifest skeletons, conjure pixies, and call forth demons from the Abyssal Waste.
        >
        > There may be more magicians in the future that also rely on essence for their magic.
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "1"
    name: Essence
    scc: mcdm.summoner.v1/feature.summoner.level-1/essence
    type: feature
name: Essence
type: feature
```
