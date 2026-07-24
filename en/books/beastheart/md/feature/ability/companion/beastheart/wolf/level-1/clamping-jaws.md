---
action_type: Maneuver
class: beastheart
companion: wolf
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the target has M < STRONG, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
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
---

*With an unnerving growl, the wolf sinks powerful teeth into their quarry.*

| **Companion, Melee, Weapon** |     **Maneuver** |
|------------------------------|-----------------:|
| **📏 Melee 1**               | **🎯 One enemy** |

**Effect:** The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.

**Spend 1 Ferocity:** If the target has M < STRONG, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the wolf.
