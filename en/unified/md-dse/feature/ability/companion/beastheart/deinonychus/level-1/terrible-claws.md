---
action_type: Maneuver
class: beastheart
companion: deinonychus
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: A target who has M < STRONG is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).
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
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: A target who has M < STRONG is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).
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
    effects:
        - effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: A target who has M < STRONG is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).
    flavor: The deinonychus kicks their prey, then slashes them with wicked claws.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Terrible Claws
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.deinonychus.level-1/terrible-claws
    subtype: signature
    target: One enemy
    type: ability
name: Terrible Claws
target: One enemy
type: feature
usage: Maneuver
```
