---
action_type: Maneuver
class: beastheart
companion: deinonychus
distance: Melee 1
effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](../../../../../../condition/bleeding.md) until the end of their next turn.
feature_type: ability
file_basename: terrible-claws
file_dpath: feature/ability/companion/beastheart/deinonychus/level-1
flavor: The deinonychus kicks their prey, then slashes them with wicked claws.
item_id: terrible-claws
item_name: Terrible Claws
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Terrible Claws
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.deinonychus.level-1/terrible-claws
source: mcdm.beastheart.v1
spend: '1 Ferocity: A target who has M < STRONG is [bleeding](../../../../../../condition/bleeding.md) (save ends).'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](../../../../../../condition/bleeding.md) until the end of their next turn.
    - effect: '1 Ferocity: A target who has M < STRONG is [bleeding](../../../../../../condition/bleeding.md) (save ends).'
      name: Spend
feature_type: ability
flavor: The deinonychus kicks their prey, then slashes them with wicked claws.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: deinonychus
    distance: Melee 1
    effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](../../../../../../condition/bleeding.md) until the end of their next turn.
    flavor: The deinonychus kicks their prey, then slashes them with wicked claws.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Terrible Claws
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.deinonychus.level-1/terrible-claws
    spend: '1 Ferocity: A target who has M < STRONG is [bleeding](../../../../../../condition/bleeding.md) (save ends).'
    subtype: signature
    target: One enemy
    type: ability
name: Terrible Claws
target: One enemy
type: feature
usage: Maneuver
```
