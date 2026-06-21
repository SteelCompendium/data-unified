---
action_type: Free triggered
class: summoner
distance: Summoner's Range
effect: Your minions act in place of you making a [free strike](../../../common/main-actions/free-strike.md) or using a [signature ability](../../../../rule/combat/signature-ability.md). If you were granted the [triggered action](../../../../rule/combat/triggered-action.md) against a specific target, your minions must strike the same target. If the [triggered action](../../../../rule/combat/triggered-action.md) granted you a [signature ability](../../../../rule/combat/signature-ability.md), you have an [edge](../../../../rule/dice/edge.md) on the [power roll](../../../../rule/dice/power-roll.md).
feature_source: summoner
feature_type: ability
file_basename: strike-for-me
file_dpath: feature/ability/summoner/level-1
flavor: Your minions fight in your stead.
item_id: strike-for-me
item_name: Strike for Me
keywords:
    - Magic
    - Ranged
level: "1"
name: Strike for Me
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/strike-for-me
source: mcdm.summoner.v1
target: Each of your minions
tier1: Up to three targets each make a [free strike](../../../common/main-actions/free-strike.md)
tier2: Up to five targets each make a [free strike](../../../common/main-actions/free-strike.md)
tier3: Up to seven targets each make a [free strike](../../../common/main-actions/free-strike.md)
trigger: You use a [triggered action](../../../../rule/combat/triggered-action.md) to make a [free strike](../../../common/main-actions/free-strike.md) or use a [signature ability](../../../../rule/combat/signature-ability.md).
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: Your minions act in place of you making a [free strike](../../../common/main-actions/free-strike.md) or using a [signature ability](../../../../rule/combat/signature-ability.md). If you were granted the [triggered action](../../../../rule/combat/triggered-action.md) against a specific target, your minions must strike the same target. If the [triggered action](../../../../rule/combat/triggered-action.md) granted you a [signature ability](../../../../rule/combat/signature-ability.md), you have an [edge](../../../../rule/dice/edge.md) on the [power roll](../../../../rule/dice/power-roll.md).
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: Up to three targets each make a [free strike](../../../common/main-actions/free-strike.md)
      tier2: Up to five targets each make a [free strike](../../../common/main-actions/free-strike.md)
      tier3: Up to seven targets each make a [free strike](../../../common/main-actions/free-strike.md)
feature_type: ability
flavor: Your minions fight in your stead.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Free triggered
    class: summoner
    distance: Summoner's Range
    effect: Your minions act in place of you making a [free strike](../../../common/main-actions/free-strike.md) or using a [signature ability](../../../../rule/combat/signature-ability.md). If you were granted the [triggered action](../../../../rule/combat/triggered-action.md) against a specific target, your minions must strike the same target. If the [triggered action](../../../../rule/combat/triggered-action.md) granted you a [signature ability](../../../../rule/combat/signature-ability.md), you have an [edge](../../../../rule/dice/edge.md) on the [power roll](../../../../rule/dice/power-roll.md).
    feature_source: summoner
    flavor: Your minions fight in your stead.
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Strike for Me
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/strike-for-me
    target: Each of your minions
    tier1: Up to three targets each make a [free strike](../../../common/main-actions/free-strike.md)
    tier2: Up to five targets each make a [free strike](../../../common/main-actions/free-strike.md)
    tier3: Up to seven targets each make a [free strike](../../../common/main-actions/free-strike.md)
    trigger: You use a [triggered action](../../../../rule/combat/triggered-action.md) to make a [free strike](../../../common/main-actions/free-strike.md) or use a [signature ability](../../../../rule/combat/signature-ability.md).
    type: ability
name: Strike for Me
target: Each of your minions
trigger: You use a [triggered action](../../../../rule/combat/triggered-action.md) to make a [free strike](../../../common/main-actions/free-strike.md) or use a [signature ability](../../../../rule/combat/signature-ability.md).
type: feature
usage: Free triggered
```
