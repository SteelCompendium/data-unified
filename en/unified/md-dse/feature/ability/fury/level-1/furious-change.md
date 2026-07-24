---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: fury
distance: Self
effects:
    - effect: You gain [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score and can enter your [animal form](scc.v1:mcdm.heroes.v1/complication/animal-form) or hybrid form.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If you are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: furious-change
file_dpath: feature/ability/fury/level-1
flavor: In your anger, you revert to a more bestial form.
item_id: furious-change
item_name: Furious Change
keywords: []
level: "1"
name: Furious Change
scc: mcdm.heroes.v1/feature.ability.fury.level-1/furious-change
source: mcdm.heroes.v1
subclass: stormwight
subtype: triggered
target: Self
trigger: You lose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You gain [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score and can enter your [animal form](scc.v1:mcdm.heroes.v1/complication/animal-form) or hybrid form.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If you are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: In your anger, you revert to a more bestial form.
keywords: []
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: fury
    distance: Self
    effects:
        - effect: You gain [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score and can enter your [animal form](scc.v1:mcdm.heroes.v1/complication/animal-form) or hybrid form.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If you are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: In your anger, you revert to a more bestial form.
    keywords: []
    level: "1"
    name: Furious Change
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/furious-change
    subclass: stormwight
    subtype: triggered
    target: Self
    trigger: You lose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
    type: ability
name: Furious Change
target: Self
trigger: You lose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
