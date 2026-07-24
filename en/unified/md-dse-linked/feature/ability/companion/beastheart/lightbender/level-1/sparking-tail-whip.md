---
action_type: Maneuver
class: beastheart
companion: lightbender
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the lightbender's Might score, and if they have M < AVERAGE, they are dazzled until the end of their next turn. A dazzled creature has line of effect only within 1 square.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: A dazzled creature also takes a bane on strikes.
feature_type: ability
file_basename: sparking-tail-whip
file_dpath: feature/ability/companion/beastheart/lightbender/level-1
flavor: The lightbender swings their tail, sending gouts of sparks in their foe's face.
item_id: sparking-tail-whip
item_name: Sparking Tail Whip
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Sparking Tail Whip
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.lightbender.level-1/sparking-tail-whip
source: mcdm.beastheart.v1
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the lightbender's Might score, and if they have M < AVERAGE, they are dazzled until the end of their next turn. A dazzled creature has line of effect only within 1 square.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: A dazzled creature also takes a bane on strikes.
feature_type: ability
flavor: The lightbender swings their tail, sending gouts of sparks in their foe's face.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: lightbender
    distance: Melee 1
    effects:
        - effect: The target takes damage equal to 3 + the lightbender's Might score, and if they have M < AVERAGE, they are dazzled until the end of their next turn. A dazzled creature has line of effect only within 1 square.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: A dazzled creature also takes a bane on strikes.
    flavor: The lightbender swings their tail, sending gouts of sparks in their foe's face.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Sparking Tail Whip
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.lightbender.level-1/sparking-tail-whip
    subtype: signature
    target: One enemy
    type: ability
name: Sparking Tail Whip
target: One enemy
type: feature
usage: Maneuver
```
