---
action_type: Maneuver
class: beastheart
companion: boar
distance: Melee 1
effects:
    - effect: The boar moves up to their speed in a straight line. When this movement ends, they can deal damage equal to 3 + their Might score to an adjacent target. If the boar moved closer to the target as part of this movement, the boar deals extra damage equal to their Might score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
feature_type: ability
file_basename: gore
file_dpath: feature/ability/companion/beastheart/boar/level-1
flavor: With an enraged snort, the boar lunges forward to rip open foes with their tusks.
item_id: gore
item_name: Gore
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Gore
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.boar.level-1/gore
source: mcdm.beastheart.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The boar moves up to their speed in a straight line. When this movement ends, they can deal damage equal to 3 + their Might score to an adjacent target. If the boar moved closer to the target as part of this movement, the boar deals extra damage equal to their Might score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
feature_type: ability
flavor: With an enraged snort, the boar lunges forward to rip open foes with their tusks.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: boar
    distance: Melee 1
    effects:
        - effect: The boar moves up to their speed in a straight line. When this movement ends, they can deal damage equal to 3 + their Might score to an adjacent target. If the boar moved closer to the target as part of this movement, the boar deals extra damage equal to their Might score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: The target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
    flavor: With an enraged snort, the boar lunges forward to rip open foes with their tusks.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Gore
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.boar.level-1/gore
    subtype: signature
    target: One creature or object
    type: ability
name: Gore
target: One creature or object
type: feature
usage: Maneuver
```
