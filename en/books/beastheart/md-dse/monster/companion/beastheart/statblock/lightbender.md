---
agility: 1
companion: lightbender
file_basename: lightbender
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
intuition: 2
item_id: lightbender
item_name: Lightbender
keywords:
    - Beast
    - Companion
level: 1
might: 2
name: Lightbender
organization: Companion
presence: 2
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/lightbender
size: 1L
skills:
    - Hide
source: mcdm.beastheart.v1
speed: 7
stability: 2
stamina: = yours
type: statblock
---

```ds-sb
agility: 1
ev: ""
features:
    - ability_type: Signature Ability
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
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.lightbender.level-1/sparking-tail-whip
      name: Sparking Tail Whip
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: Any effect on the lightbender that would be ended by a saving throw instead ends automatically at the end of their next turn.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.lightbender.level-1/avoidance
      name: Avoidance
      type: feature
free_strike: 1 + M
intuition: 2
keywords:
    - Beast
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/lightbender
    source: mcdm.beastheart.v1
might: 2
name: Lightbender
organization: Companion
presence: 2
reason: -1
role: ""
size: 1L
skills:
    - Hide
speed: 7
stability: 2
stamina: = yours
type: statblock
```
