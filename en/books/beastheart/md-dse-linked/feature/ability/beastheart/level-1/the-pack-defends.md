---
action_type: Triggered Action
class: beastheart
distance: Melee 1
effect: The target takes half the damage.
feature_type: ability
file_basename: the-pack-defends
file_dpath: feature/ability/beastheart/level-1
flavor: You siphon away the pain and endure it yourself.
item_id: the-pack-defends
item_name: The Pack Defends
keywords:
    - Magic
level: "1"
name: The Pack Defends
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/the-pack-defends
source: mcdm.beastheart.v1
spend: '1 Ferocity: You spend a Recovery without regaining Stamina, and the target regains Stamina equal to your recovery value.'
subclass: guardian
target: One ally
trigger: The target takes damage.
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes half the damage.
    - effect: '1 Ferocity: You spend a Recovery without regaining Stamina, and the target regains Stamina equal to your recovery value.'
      name: Spend
feature_type: ability
flavor: You siphon away the pain and endure it yourself.
keywords:
    - Magic
metadata:
    action_type: Triggered Action
    class: beastheart
    distance: Melee 1
    effect: The target takes half the damage.
    flavor: You siphon away the pain and endure it yourself.
    keywords:
        - Magic
    level: "1"
    name: The Pack Defends
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/the-pack-defends
    spend: '1 Ferocity: You spend a Recovery without regaining Stamina, and the target regains Stamina equal to your recovery value.'
    subclass: guardian
    target: One ally
    trigger: The target takes damage.
    type: ability
name: The Pack Defends
target: One ally
trigger: The target takes damage.
type: feature
usage: Triggered Action
```
