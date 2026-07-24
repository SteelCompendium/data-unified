---
action_type: Maneuver
class: beastheart
distance: Self
effects:
    - effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](../../../../movement/teleport.md) to your space from any distance, even if they don't have line of effect to you.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: Your partner can [shift](../../../../movement/shifting.md) up to their speed.
    - cost: Spend 1–5 Ferocity
      effect: Your partner gains additional temporary Stamina equal to their Might score for each ferocity spent this way.
    - cost: Spend 5 Ferocity
      effect: You restore your dead partner to life with 1 Stamina, even if their body was destroyed. They gain no temporary Stamina if you use this ability this way.
feature_type: ability
file_basename: heart-of-the-beast
file_dpath: feature/ability/beastheart/level-1
flavor: '"Better look away—this might not be pretty."'
item_id: heart-of-the-beast
item_name: Heart of the Beast
keywords:
    - Magic
    - Ranged
level: "1"
name: Heart of the Beast
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/heart-of-the-beast
source: mcdm.beastheart.v1
target: Self
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](../../../../movement/teleport.md) to your space from any distance, even if they don't have line of effect to you.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: Your partner can [shift](../../../../movement/shifting.md) up to their speed.
    - cost: Spend 1–5 Ferocity
      effect: Your partner gains additional temporary Stamina equal to their Might score for each ferocity spent this way.
    - cost: Spend 5 Ferocity
      effect: You restore your dead partner to life with 1 Stamina, even if their body was destroyed. They gain no temporary Stamina if you use this ability this way.
feature_type: ability
flavor: '"Better look away—this might not be pretty."'
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Self
    effects:
        - effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](../../../../movement/teleport.md) to your space from any distance, even if they don't have line of effect to you.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: Your partner can [shift](../../../../movement/shifting.md) up to their speed.
        - cost: Spend 1–5 Ferocity
          effect: Your partner gains additional temporary Stamina equal to their Might score for each ferocity spent this way.
        - cost: Spend 5 Ferocity
          effect: You restore your dead partner to life with 1 Stamina, even if their body was destroyed. They gain no temporary Stamina if you use this ability this way.
    flavor: '"Better look away—this might not be pretty."'
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Heart of the Beast
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/heart-of-the-beast
    target: Self
    type: ability
name: Heart of the Beast
target: Self
type: feature
usage: Maneuver
```
