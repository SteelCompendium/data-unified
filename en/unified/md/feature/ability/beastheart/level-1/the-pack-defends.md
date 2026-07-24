---
action_type: Triggered Action
class: beastheart
distance: Melee 1
effects:
    - effect: The target takes half the damage.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: You spend a Recovery without regaining Stamina, and the target regains Stamina equal to your recovery value.
flavor: You siphon away the pain and endure it yourself.
keywords:
    - Magic
level: "1"
name: The Pack Defends
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/the-pack-defends
subclass: guardian
target: One ally
trigger: The target takes damage.
type: ability
---

*You siphon away the pain and endure it yourself.*

| **Magic**      | **Triggered Action** |
|----------------|---------------------:|
| **📏 Melee 1** |      **🎯 One ally** |

**Trigger:** The target takes damage.

**Effect:** The target takes half the damage.

**Spend 1 Ferocity:** You spend a Recovery without regaining Stamina, and the target regains Stamina equal to your recovery value.
