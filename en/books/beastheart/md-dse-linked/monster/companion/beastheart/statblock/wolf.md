---
agility: 2
companion: wolf
file_basename: wolf
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
intuition: 2
item_id: wolf
item_name: Wolf
keywords:
    - Animal
    - Companion
level: 1
might: 2
name: Wolf
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/wolf
size: 1M
skills:
    - Track
source: mcdm.beastheart.v1
speed: 7
stability: 1
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
        - effect: The target takes damage equal to 3 + the wolf's Might score, and if they have M < AVERAGE, they are [grabbed](../../../../condition/grabbed.md) by the wolf.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the target has M < STRONG, they are [grabbed](../../../../condition/grabbed.md) by the wolf.
      feature_type: ability
      flavor: With an unnerving growl, the wolf sinks powerful teeth into their quarry.
      keywords:
        - Companion
        - Melee
        - Weapon
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.wolf.level-1/clamping-jaws
      name: Clamping Jaws
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: The wolf can move at full speed while they have a creature [grabbed](../../../../condition/grabbed.md), no matter the [grabbed](../../../../condition/grabbed.md) creature's size.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.wolf.level-1/retriever
      name: Retriever
      type: feature
free_strike: 1 + M
intuition: 2
keywords:
    - Animal
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/wolf
    source: mcdm.beastheart.v1
might: 2
name: Wolf
organization: Companion
presence: 1
reason: -1
role: ""
size: 1M
skills:
    - Track
speed: 7
stability: 1
stamina: = yours
type: statblock
```
