---
agility: 2
companion: gummy-ball
file_basename: gummy-ball
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Acid 3
intuition: 2
item_id: gummy-ball
item_name: Gummy Ball
keywords:
    - Companion
    - Ooze
level: 1
might: 2
name: Gummy Ball
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/gummy-ball
size: 1L
skills:
    - Sneak
source: mcdm.beastheart.v1
speed: 5
stability: 2
stamina: = yours
type: statblock
---

```ds-sb
agility: 2
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - effect: The target takes acid damage equal to 3 + the ball's Might score, and if they have A < AVERAGE, the ball moves into the target's space. If the target completely fits within the ball's space, the target is [grabbed](../../../../condition/grabbed.md) by the ball.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: A target [grabbed](../../../../condition/grabbed.md) this way takes acid damage equal to the ball's Might score at the end of each of the ball's turns.
      feature_type: ability
      flavor: With a sickening squelch, the ball oozes around their hapless prey.
      keywords:
        - Companion
        - Melee
        - Weapon
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.gummy-ball.level-1/absorb
      name: Absorb
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: The ball can occupy another creature's space. While occupying a creature's space, the ball has line of effect to that creature. If the creature completely fits within the ball's space, the creature has line of effect only to the ball and creatures outside the ball don't have line of effect to the creature. The ball's space is [difficult terrain](../../../../movement/difficult-terrain.md).
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.gummy-ball.level-1/gelatinous
      name: Gelatinous
      type: feature
free_strike: 1 + M
immunities:
    - Acid 3
intuition: 2
keywords:
    - Companion
    - Ooze
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/gummy-ball
    source: mcdm.beastheart.v1
might: 2
name: Gummy Ball
organization: Companion
presence: 1
reason: -1
role: ""
size: 1L
skills:
    - Sneak
speed: 5
stability: 2
stamina: = yours
type: statblock
```
