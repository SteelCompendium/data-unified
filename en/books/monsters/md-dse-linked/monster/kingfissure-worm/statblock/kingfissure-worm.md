---
agility: 1
ev: "108"
file_basename: kingfissure-worm
file_dpath: monster/kingfissure-worm/statblock
free_strike: 8
intuition: 2
item_id: kingfissure-worm
item_name: Kingfissure Worm
keywords:
    - Beast
    - Worm
level: 7
might: 5
movement: Burrow
name: Kingfissure Worm
organization: Solo
presence: -3
reason: -5
scc: mcdm.monsters.v1/monster.kingfissure-worm.statblock/kingfissure-worm
size: "5"
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: "420"
type: statblock
---

```ds-sb
agility: 1
ev: "108"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the kingfissure worm can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** The kingfissure worm can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The kingfissure worm has three tongues. Each tongue is a 5 x 1 line within 1 square of the kingfissure worm, has 35 [Stamina](../../../rule/health/stamina.md) and psychic immunity all, and can't be [force moved](../../../movement/forced-movement.md). Each tongue enables the kingfissure worm to [grab](../../../condition/grabbed.md) one size 3 or smaller creature or object. A tongue can be targeted by abilities only while it has a target [grabbed](../../../condition/grabbed.md).
      feature_type: trait
      icon: ⭐️
      name: Multiple Tongues
      type: feature
    - ability_type: Signature Ability
      distance: Melee 5
      effects:
        - roll: Power Roll + 5
          tier1: 13 damage; M < 3 [grabbed](../../../condition/grabbed.md)
          tier2: 18 damage; M < 4 [grabbed](../../../condition/grabbed.md)
          tier3: 22 damage; M < 5 [grabbed](../../../condition/grabbed.md) and the target takes a bane on the Escape Grab maneuver
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tongue Grab
      target: One creature or object per tongue
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; [push](../../../movement/forced-movement.md) 3
          tier2: 20 damage; [push](../../../movement/forced-movement.md) 5, [prone](../../../condition/prone.md)
          tier3: 25 damage; the target is swallowed (see Swallowed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Maw
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - effect: '**Effect:** The target is swallowed (see Swallowed).'
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Consume
      target: One grabbed creature
      type: feature
      usage: Main action
    - distance: Melee 5 or ranged 10
      effects:
        - effect: '**Effect:** The kingfissure worm can use this maneuver only while they have a creature or object [grabbed](../../../condition/grabbed.md). The worm slams the [grabbed](../../../condition/grabbed.md) creature or object against the target, dealing 13 damage to both. If this ability is used at range, it deals an extra 5 damage and the [grabbed](../../../condition/grabbed.md) creature or object is released.'
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Tongue Whip
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** A tongue takes damage that doesn't reduce it to 0 [Stamina](../../../rule/health/stamina.md).
            **Effect:** The kingfissure worm deals 5 damage to the creature or object the tongue had [grabbed](../../../condition/grabbed.md), releases that creature or object, then pulls the damaged tongue back into their mouth.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Tearing Recoil
      target: Special
      type: feature
      usage: Triggered action
    - effects:
        - effect: The kingfissure worm has line of effect only within 3 squares However, they ignore concealment for creatures touching the ground and don't need line of effect to use abilities against those creatures.
      feature_type: trait
      icon: ⭐️
      name: Seismic King
      type: feature
    - effects:
        - effect: A creature swallowed by the kingfissure worm is [restrained](../../../condition/restrained.md) and takes 1d6 acid damage at the start of every turn. If the worm takes 25 or more damage in a single round from swallowed creatures, they immediately regurgitate all creatures they have swallowed, who land [prone](../../../condition/prone.md) in unoccupied spaces within 3 squares of the kingfissure worm.
      feature_type: trait
      icon: ⭐️
      name: Swallowed
      type: feature
    - effects:
        - effect: The kingfissure worm can [burrow](../../../movement/burrow.md) through stone. When the worm burrows, they create a stable size 3 tunnel in the squares they move through.
      feature_type: trait
      icon: ⭐️
      name: Titanic Tunneler
      type: feature
    - effects:
        - effect: The kingfissure worm can't be [frightened](../../../condition/frightened.md) or knocked [prone](../../../condition/prone.md). While the worm is [restrained](../../../condition/restrained.md) or [slowed](../../../condition/slowed.md), they take a −2 penalty to speed instead of suffering those conditions' usual effects on speed.
      feature_type: trait
      icon: ⭐️
      name: Unstoppable Crawler
      type: feature
    - cost: Villain Action 1
      distance: 20 x 4 line within 1
      effects:
        - roll: ""
          tier1: 10 damage; the target falls into the fissure, lands [prone](../../../condition/prone.md), and can't stand (EoT)
          tier2: 10 damage; the target is knocked [prone](../../../condition/prone.md) and left hanging at the edge of the area
          tier3: The target [shifts](../../../movement/shifting.md) to the nearest unoccupied space outside the area.
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: King's Fissure
      target: Each creature and object in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** The kingfissure worm can use this villain action only while burrowing. The worm burrows up to half their speed, then breaches the surface and moves 5 squares straight up before dropping back to the ground. Each creature or object whose space the worm moves through during this movement takes 10 damage, and if they have A < 4 they are knocked [prone](../../../condition/prone.md). Any creature who is made [winded](../../../rule/health/winded.md) by this damage is swallowed (see Swallowed).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Weapon
      name: Earth Breach
      target: Special
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - roll: Power Roll + 5
          tier1: 8 acid damage; P < 3 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 13 acid damage; P < 4 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 17 acid damage; P < 5 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: Better Out Than In
      target: Each enemy and object in the area
      type: feature
      usage: '-'
free_strike: 8
intuition: 2
keywords:
    - Beast
    - Worm
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.kingfissure-worm.statblock/kingfissure-worm
    source: mcdm.monsters.v1
might: 5
movement: Burrow
name: Kingfissure Worm
organization: Solo
presence: -3
reason: -5
role: ""
size: "5"
speed: 10
stability: 5
stamina: "420"
type: statblock
```
