---
agility: 1
companion: drake
file_basename: drake
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Attuned damage type 3 (see Elementally Attuned)
intuition: 2
item_id: drake
item_name: Drake
keywords:
    - Companion
    - Dragon
level: 1
might: 2
movement: Fly
name: Drake
organization: Companion
presence: 2
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/drake
size: 1M
skills:
    - Intimidate
source: mcdm.beastheart.v1
speed: 5
stability: 1
stamina: = yours
type: statblock
---

```ds-sb
agility: 1
ev: ""
features:
    - ability_type: Signature Ability
      distance: 1 or 2 cube within 1
      effects:
        - effect: The target takes damage of the drake's attuned damage type (see [Elementally Attuned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/elementally-attuned)) equal to the drake's Might score.
          name: Effect
        - cost: Spend 1 or 2 Ferocity
          effect: This ability affects a 3 cube (if you spend 1 ferocity) or a 4 cube (if you spend 2 ferocity) within 1.
      feature_type: ability
      flavor: The drake exhales a blast of flesh-melting energy.
      keywords:
        - Area
        - Companion
        - Magic
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.drake.level-1/drake-breath
      name: Drake Breath
      target: Each creature in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: When you gain this companion, you choose their attuned damage type from acid, cold, corruption, fire, lightning, poison, or sonic. The drake's attuned damage type affects their other features.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/elementally-attuned
      name: Elementally Attuned
      type: feature
    - effects:
        - effect: You have immunity 3 to the drake's attuned damage type.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.drake.level-1/shared-scales
      name: Shared Scales
      type: feature
free_strike: 1 + M
immunities:
    - Attuned damage type 3 (see Elementally Attuned)
intuition: 2
keywords:
    - Companion
    - Dragon
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/drake
    source: mcdm.beastheart.v1
might: 2
movement: Fly
name: Drake
organization: Companion
presence: 2
reason: -1
role: ""
size: 1M
skills:
    - Intimidate
speed: 5
stability: 1
stamina: = yours
type: statblock
```
