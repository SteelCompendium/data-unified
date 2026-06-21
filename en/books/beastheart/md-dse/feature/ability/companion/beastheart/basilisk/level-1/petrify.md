---
action_type: Maneuver
class: beastheart
companion: basilisk
distance: Melee 1 or ranged 5
effect: The target takes corruption damage equal to 3 + the basilisk's Might score and is stoned (save ends) (see [Stoned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.basilisk.level-1/stoned)).
feature_type: ability
file_basename: petrify
file_dpath: feature/ability/companion/beastheart/basilisk/level-1
flavor: Transfixed by the basilisk's magical gaze or struck by their poisoned claws, the foe's body begins to calcify.
item_id: petrify
item_name: Petrify
keywords:
    - Companion
    - Magic
    - Melee
    - Ranged
    - Weapon
level: "1"
name: Petrify
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.basilisk.level-1/petrify
source: mcdm.beastheart.v1
spend: '1 Ferocity: While stoned this way, the target is also [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1 or ranged 5
effects:
    - effect: The target takes corruption damage equal to 3 + the basilisk's Might score and is stoned (save ends) (see [Stoned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.basilisk.level-1/stoned)).
    - effect: '1 Ferocity: While stoned this way, the target is also [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).'
      name: Spend
feature_type: ability
flavor: Transfixed by the basilisk's magical gaze or struck by their poisoned claws, the foe's body begins to calcify.
keywords:
    - Companion
    - Magic
    - Melee
    - Ranged
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: basilisk
    distance: Melee 1 or ranged 5
    effect: The target takes corruption damage equal to 3 + the basilisk's Might score and is stoned (save ends) (see [Stoned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.basilisk.level-1/stoned)).
    flavor: Transfixed by the basilisk's magical gaze or struck by their poisoned claws, the foe's body begins to calcify.
    keywords:
        - Companion
        - Magic
        - Melee
        - Ranged
        - Weapon
    level: "1"
    name: Petrify
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.basilisk.level-1/petrify
    spend: '1 Ferocity: While stoned this way, the target is also [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).'
    subtype: signature
    target: One enemy
    type: ability
name: Petrify
target: One enemy
type: feature
usage: Maneuver
```
