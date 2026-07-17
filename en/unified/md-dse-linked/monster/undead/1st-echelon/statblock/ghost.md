---
agility: 2
ev: "12"
file_basename: ghost
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 4
immunities:
    - Corruption 3
    - poison 3
intuition: 0
item_id: ghost
item_name: Ghost
keywords:
    - Undead
level: 1
might: -2
movement: Fly, hover
name: Ghost
organization: Leader
presence: 3
reason: 0
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghost
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "80"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 7 cold damage; P < 1 [slowed](../../../../condition/slowed.md) (save ends)
          tier2: 10 cold damage; P < 2 [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 13 cold damage; P < 3 [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Heat Death
      target: Two creatures
      type: feature
      usage: Main action
    - distance: Ranged 8
      effects:
        - effect: |-
            **Effect:** The target [shifts](../../../../movement/shifting.md) up to their speed.
            **2 [Malice](../../../../rule/monster/malice.md):** The ghost chooses one additional target.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Haunt
      target: Self or one ally with a Phasing trait
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature within distance targets the ghost with a strike.
            **Effect:** The ghost halves the damage from the strike and the target takes 2 sonic damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Melee
      name: Shriek
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: Each undead with a Phasing trait within 10 squares of the ghost can't be made [slowed](../../../../condition/slowed.md) or [weakened](../../../../condition/weakened.md).
      feature_type: trait
      icon: ⭐️
      name: Phantom Flow
      type: feature
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target rises 1 square into the air and is vertically [pulled](../../../../movement/forced-movement.md) up to 5 squares toward the nearest enemy within 3 squares of the target.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Paranormal Activity
      target: Each size 3 or smaller object in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - roll: Power Roll + 3
          tier1: P < 1 the target is levitated (EoT)
          tier2: P < 2 the target is levitated (EoT)
          tier3: P < 3 the target is levitated until the end of the encounter
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Spirited Away
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - roll: Power Roll + 3
          tier1: 3 sonic damage
          tier2: 5 sonic damage
          tier3: 8 sonic damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Awful Wail
      target: Each enemy in the area
      type: feature
      usage: '-'
    - effects:
        - effect: The ghost can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the ghost moves through a creature, that creature takes 2 corruption damage. The ghost doesn't take damage from being [force moved](../../../../movement/forced-movement.md) into objects.
      feature_type: trait
      icon: ⭐️
      name: Corruptive Phasing
      type: feature
free_strike: 4
immunities:
    - Corruption 3
    - poison 3
intuition: 0
keywords:
    - Undead
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghost
    source: mcdm.monsters.v1
might: -2
movement: Fly, hover
name: Ghost
organization: Leader
presence: 3
reason: 0
role: ""
size: 1M
speed: 6
stability: 1
stamina: "80"
type: statblock
```
