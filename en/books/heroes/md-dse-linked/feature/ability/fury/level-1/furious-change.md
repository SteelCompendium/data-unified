---
action_type: Triggered
class: fury
distance: Self
effect: You gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Might](../../../../rule/character/might.md) score and can enter your [animal form](../../../../complication/animal-form.md) or hybrid form.
feature_type: ability
file_basename: furious-change
file_dpath: feature/ability/fury/level-1
flavor: In your anger, you revert to a more bestial form.
item_id: furious-change
item_name: Furious Change
keywords:
    - '-'
level: "1"
name: Furious Change
scc: mcdm.heroes.v1/feature.ability.fury.level-1/furious-change
source: mcdm.heroes.v1
spend: '1 Ferocity: If you are not [dying](../../../../rule/health/dying.md), you can spend a [Recovery](../../../../rule/health/recoveries.md).'
subtype: triggered
target: Self
trigger: You lose [Stamina](../../../../rule/health/stamina.md) and are not [dying](../../../../rule/health/dying.md).
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Might](../../../../rule/character/might.md) score and can enter your [animal form](../../../../complication/animal-form.md) or hybrid form.
    - effect: '1 Ferocity: If you are not [dying](../../../../rule/health/dying.md), you can spend a [Recovery](../../../../rule/health/recoveries.md).'
      name: Spend
feature_type: ability
flavor: In your anger, you revert to a more bestial form.
keywords:
    - '-'
metadata:
    action_type: Triggered
    class: fury
    distance: Self
    effect: You gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your [Might](../../../../rule/character/might.md) score and can enter your [animal form](../../../../complication/animal-form.md) or hybrid form.
    flavor: In your anger, you revert to a more bestial form.
    keywords:
        - '-'
    level: "1"
    name: Furious Change
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/furious-change
    spend: '1 Ferocity: If you are not [dying](../../../../rule/health/dying.md), you can spend a [Recovery](../../../../rule/health/recoveries.md).'
    subtype: triggered
    target: Self
    trigger: You lose [Stamina](../../../../rule/health/stamina.md) and are not [dying](../../../../rule/health/dying.md).
    type: ability
name: Furious Change
target: Self
trigger: You lose [Stamina](../../../../rule/health/stamina.md) and are not [dying](../../../../rule/health/dying.md).
type: feature
usage: Triggered
```
