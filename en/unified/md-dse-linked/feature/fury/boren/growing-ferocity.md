---
action_type: feature
class: fury
feature_type: feature
file_basename: growing-ferocity
file_dpath: feature/fury/boren
item_id: growing-ferocity
item_name: Growing Ferocity
kit: boren
name: Growing Ferocity
scc: mcdm.heroes.v1/feature.fury.boren/growing-ferocity
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        As your ferocity grows, you gain benefits as noted on the [Boren](../../../kit/boren.md) [Growing Ferocity](growing-ferocity.md) table. Benefits are cumulative except where an improved benefit replaces a lesser benefit.

        ###### Boren Growing Ferocity Table

        | Ferocity        | Benefit                                                                                                                                                                                                                   |
        |-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
        | 2               | You can have up to two creatures [grabbed](../../../condition/grabbed.md) at a time. Additionally, whenever you make a [strike](../../../rule/combat/strike.md) against a creature you have [grabbed](../../../condition/grabbed.md), you gain 1 [surge](../../../rule/resource/surge.md).                                                                       |
        | 4               | The first time you grab a creature on a [turn](../../../rule/combat/turn.md), you gain 1 [surge](../../../rule/resource/surge.md).                                                                                                                                                           |
        | 6               | You gain an [edge](../../../rule/dice/edge.md) on the [Grab](../../common/maneuvers/grab.md) and [Knockback](../../common/maneuvers/knockback.md) maneuvers.                                                                                                                                                                     |
        | 8 (4th level)   | The first time you grab a creature on a [turn](../../../rule/combat/turn.md), you gain 2 [surges](../../../rule/resource/surge.md) instead of 1.                                                                                                                                             |
        | 10 (7th level)  | You have a double [edge](../../../rule/dice/edge.md) on the [Grab](../../common/maneuvers/grab.md) and [Knockback](../../common/maneuvers/knockback.md) maneuvers.                                                                                                                                                               |
        | 12 (10th level) | Whenever you use a [heroic ability](../../../rule/general/heroic-ability.md), you gain 10 [temporary Stamina](../../../rule/health/temporary-stamina.md). Additionally, whenever you have a creature [grabbed](../../../condition/grabbed.md), any [ability roll](../../../rule/dice/ability-roll.md) made against that creature gains a [bonus](../../../rule/dice/bonuses-and-penalties.md) to its [potency](../../../rule/character/potency.md) equal to your [Might](../../../rule/character/might.md) score. |
feature_type: feature
metadata:
    class: fury
    kit: boren
    name: Growing Ferocity
    scc: mcdm.heroes.v1/feature.fury.boren/growing-ferocity
    type: feature
name: Growing Ferocity
type: feature
```
