---
action_type: Maneuver
class: beastheart
distance: Self
effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to your space from any distance, even if they don't have line of effect to you.
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
spend: '1 Ferocity: Your partner can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed.'
target: Self
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to your space from any distance, even if they don't have line of effect to you.
    - effect: '1 Ferocity: Your partner can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed.'
      name: Spend
feature_type: ability
flavor: '"Better look away—this might not be pretty."'
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Self
    effect: You must spend a Recovery without regaining Stamina. Your partner gains temporary Stamina equal to your recovery value as they leap out of your chest. Your partner [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to your space from any distance, even if they don't have line of effect to you.
    flavor: '"Better look away—this might not be pretty."'
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Heart of the Beast
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/heart-of-the-beast
    spend: '1 Ferocity: Your partner can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed.'
    target: Self
    type: ability
name: Heart of the Beast
target: Self
type: feature
usage: Maneuver
```
