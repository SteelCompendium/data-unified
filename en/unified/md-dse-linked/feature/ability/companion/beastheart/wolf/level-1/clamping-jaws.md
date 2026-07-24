---
action_type: Maneuver
class: beastheart
companion: wolf
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
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
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
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
    effects:
        - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the target has M < STRONG, they are [grabbed](../../../../../../condition/grabbed.md) by the wolf.
    flavor: With an unnerving growl, the wolf sinks powerful teeth into their quarry.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Clamping Jaws
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.wolf.level-1/clamping-jaws
    subtype: signature
    target: One enemy
    type: ability
name: Clamping Jaws
target: One enemy
type: feature
usage: Maneuver
```
