---
agility: 2
companion: sporeling
file_basename: sporeling
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Poison 3
intuition: 2
item_id: sporeling
item_name: Sporeling
keywords:
    - Beast
    - Companion
level: 1
might: 2
name: Sporeling
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/sporeling
size: 1S
skills:
    - Track
source: mcdm.beastheart.v1
speed: 5
stability: 0
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
        - effect: The target takes poison damage equal to 3 + the sporeling's Might score, and the sporeling is invisible to the target until the end of the sporeling's next turn or they deal damage to the target.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the target has M < STRONG, they are [dazed](../../../../condition/dazed.md) until the end of their next turn.
      feature_type: ability
      flavor: The sporeling breathes a cloud of disorienting fumes.
      keywords:
        - Companion
        - Melee
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.sporeling.level-1/spore-puff
      name: Spore Puff
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: The sporeling can end their movement in an ally's space. While occupying an ally's space, the sporeling has cover.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.sporeling.level-1/skulker
      name: Skulker
      type: feature
free_strike: 1 + M
immunities:
    - Poison 3
intuition: 2
keywords:
    - Beast
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/sporeling
    source: mcdm.beastheart.v1
might: 2
name: Sporeling
organization: Companion
presence: 1
reason: -1
role: ""
size: 1S
skills:
    - Track
speed: 5
stability: 0
stamina: = yours
type: statblock
```
