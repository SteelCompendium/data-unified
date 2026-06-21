---
action_type: Maneuver
class: beastheart
companion: drake
distance: 1 or 2 cube within 1
effect: The target takes damage of the drake's attuned damage type (see [Elementally Attuned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/elementally-attuned)) equal to the drake's Might score.
feature_type: ability
file_basename: drake-breath
file_dpath: feature/ability/companion/beastheart/drake/level-1
flavor: The drake exhales a blast of flesh-melting energy.
item_id: drake-breath
item_name: Drake Breath
keywords:
    - Area
    - Companion
    - Magic
level: "1"
name: Drake Breath
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.drake.level-1/drake-breath
source: mcdm.beastheart.v1
spend: '1 or 2 Ferocity: This ability affects a 3 cube (if you spend 1 ferocity) or a 4 cube (if you spend 2 ferocity) within 1.'
subtype: signature
target: Each creature in the area
type: ability
---

```ds-feature
distance: 1 or 2 cube within 1
effects:
    - effect: The target takes damage of the drake's attuned damage type (see [Elementally Attuned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/elementally-attuned)) equal to the drake's Might score.
    - effect: '1 or 2 Ferocity: This ability affects a 3 cube (if you spend 1 ferocity) or a 4 cube (if you spend 2 ferocity) within 1.'
      name: Spend
feature_type: ability
flavor: The drake exhales a blast of flesh-melting energy.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Maneuver
    class: beastheart
    companion: drake
    distance: 1 or 2 cube within 1
    effect: The target takes damage of the drake's attuned damage type (see [Elementally Attuned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/elementally-attuned)) equal to the drake's Might score.
    flavor: The drake exhales a blast of flesh-melting energy.
    keywords:
        - Area
        - Companion
        - Magic
    level: "1"
    name: Drake Breath
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.drake.level-1/drake-breath
    spend: '1 or 2 Ferocity: This ability affects a 3 cube (if you spend 1 ferocity) or a 4 cube (if you spend 2 ferocity) within 1.'
    subtype: signature
    target: Each creature in the area
    type: ability
name: Drake Breath
target: Each creature in the area
type: feature
usage: Maneuver
```
