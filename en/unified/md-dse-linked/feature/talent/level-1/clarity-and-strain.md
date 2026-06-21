---
action_type: feature
class: talent
feature_type: feature
file_basename: clarity-and-strain
file_dpath: feature/talent/level-1
item_id: clarity-and-strain
item_name: Clarity and Strain
level: "1"
name: Clarity and Strain
scc: mcdm.heroes.v1/feature.talent.level-1/clarity-and-strain
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        The focus and precision of your thoughts grant you a [Heroic Resource](../../../rule/resource/heroic-resource.md) called clarity that empowers your psionic abilities.

        ##### Clarity in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](../../../rule/combat/combat-round.md) (as determined by the Director), you gain clarity equal to your [Victories](../../../rule/resource/victories.md). At the start of each of your [turns](../../../rule/combat/turn.md) during combat, you gain 1d3 clarity.

        Additionally, the first time each [combat round](../../../rule/combat/combat-round.md) that a creature is [force moved](../../../movement/forced-movement.md), you gain 1 clarity.

        You can spend clarity you don't have, pushing that [Heroic Resource](../../../rule/resource/heroic-resource.md) into negative numbers to a maximum negative value equal to 1 + your [Reason](../../../rule/character/reason.md) score. At the end of each of your [turns](../../../rule/combat/turn.md), you take 1 damage for each negative point of clarity.

        Whenever you have clarity below 0, you are strained. Some psionic abilities have additional effects if you are already strained or become strained when you use them. Strained effects can still impact you even after you are no longer strained.

        You lose any remaining clarity or reset any negative clarity at the end of the encounter.

        ##### Clarity Outside of Combat

        Though you can't gain clarity outside of combat, you can use your [heroic abilities](../../../rule/general/heroic-ability.md) and effects that cost clarity without spending it. Whenever you use an ability or effect outside of combat that costs clarity, you can't use that same ability or effect outside of combat again until you earn 1 or more [Victories](../../../rule/resource/victories.md) or finish a [respite](../../../rule/resource/respite.md).

        Additionally, whenever you use any ability or effect that costs clarity within 1 minute of using another such ability, you take 1d6 damage and incur any strain effect from using the new ability. Whenever you use an ability with a strain effect outside of combat, you can take 1d6 damage and incur the effect if you don't incur it for other reasons.

        When you use an ability outside of combat that lets you spend unlimited clarity on its effect, such as [Minor Telekinesis](../../ability/talent/level-1/minor-telekinesis.md), you can use it as if you had spent an amount of clarity equal to your [Victories](../../../rule/resource/victories.md).
feature_type: feature
metadata:
    class: talent
    level: "1"
    name: Clarity and Strain
    scc: mcdm.heroes.v1/feature.talent.level-1/clarity-and-strain
    type: feature
name: Clarity and Strain
type: feature
```
