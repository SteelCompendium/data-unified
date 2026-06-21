---
action_type: Maneuver
class: beastheart
companion: wolf
distance: Melee 1
effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
feature_type: ability
file_basename: clamping-jaws
file_dpath: feature/ability/companion/beastheart/wolf/level-1
flavor: With an unnerving growl, the wolf sinks powerful teeth into their quarry.
item_id: clamping-jaws
item_name: Clamping Jaws
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Clamping Jaws
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.wolf.level-1/clamping-jaws
source: mcdm.beastheart.v1
spend: '1 Ferocity: If the target has M < STRONG, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
    - effect: '1 Ferocity: If the target has M < STRONG, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.'
      name: Spend
feature_type: ability
flavor: With an unnerving growl, the wolf sinks powerful teeth into their quarry.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: wolf
    distance: Melee 1
    effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
    flavor: With an unnerving growl, the wolf sinks powerful teeth into their quarry.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Clamping Jaws
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.wolf.level-1/clamping-jaws
    spend: '1 Ferocity: If the target has M < STRONG, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.'
    subtype: signature
    target: One enemy
    type: ability
name: Clamping Jaws
target: One enemy
type: feature
usage: Maneuver
```
