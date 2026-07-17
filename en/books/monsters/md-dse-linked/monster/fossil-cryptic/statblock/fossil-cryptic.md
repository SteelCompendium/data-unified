---
agility: 2
ev: "48"
file_basename: fossil-cryptic
file_dpath: monster/fossil-cryptic/statblock
free_strike: 5
intuition: 1
item_id: fossil-cryptic
item_name: Fossil Cryptic
keywords:
    - Elemental
level: 2
might: 3
movement: Burrow
name: Fossil Cryptic
organization: Solo
presence: 0
reason: 1
scc: mcdm.monsters.v1/monster.fossil-cryptic.statblock/fossil-cryptic
size: 1L
source: mcdm.monsters.v1
speed: 8
stability: 3
stamina: "250"
type: statblock
---

```ds-sb
agility: 2
ev: "48"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the cryptic can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
            **Solo Turns:** The cryptic can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The cryptic is constantly surrounded by a 1 aura of swirling debris that obscures their form. Ranged abilities that target the cryptic take a bane. Additionally, any enemy who enters the aura for the first time in a round or starts their turn there takes 5 damage.
      feature_type: trait
      icon: ⭐️
      name: Churning Trunk
      type: feature
    - effects:
        - effect: The cryptic ignores [difficult terrain](../../../movement/difficult-terrain.md). Additionally, they have line of effect to any creature with concealment if that creature is touching the ground.
      feature_type: trait
      icon: ⭐️
      name: Seismic Step
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; A < 1 [slide](../../../movement/forced-movement.md) 2
          tier2: 12 damage; A < 2 [slide](../../../movement/forced-movement.md) 2, [prone](../../../condition/prone.md)
          tier3: 15 damage; A < 3 [slide](../../../movement/forced-movement.md) 3, [prone](../../../condition/prone.md) and can't stand (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Sand Slam
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 6 x 1 line within 1
      effects:
        - roll: Power Roll + 3
          tier1: 4 damage; M < 1 [push](../../../movement/forced-movement.md) 2
          tier2: 7 damage; M < 2 [prone](../../../condition/prone.md)
          tier3: 10 damage; M < 3 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Stone Bone Storm
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: |-
            **Effect:** The cryptic [slides](../../../movement/forced-movement.md) the target up to 3 squares.
            **2 [Malice](../../../rule/monster/malice.md):** The ability targets one additional target.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Stoneshift
      target: One creature or object on the ground
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The cryptic takes damage.
            **Effect:** The cryptic halves the damage, ignores any nondamaging effects associated with it, and [shifts](../../../movement/shifting.md) up to 3 squares.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Dissipate
      target: Self
      type: feature
      usage: Triggered action
    - cost: 5 Malice
      distance: 2 burst
      effects:
        - roll: Power Roll + 3
          tier1: 4 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 7 damage; [push](../../../movement/forced-movement.md) 3, [prone](../../../condition/prone.md)
          tier3: 10 damage; [push](../../../movement/forced-movement.md) 4, [prone](../../../condition/prone.md)
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Shatterstone
      target: Each enemy in the area
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - roll: ""
          tier1: '[Prone](../../../condition/prone.md) and can''t stand (EoT)'
          tier2: '[Prone](../../../condition/prone.md)'
          tier3: No effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: First Warning Quake
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - roll: ""
          tier1: 9 damage; [prone](../../../condition/prone.md)
          tier2: 5 damage
          tier3: The target moves to the nearest unoccupied space outside the area.
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Final Warning Fissure
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 2 damage; vertical [slide](../../../movement/forced-movement.md) 2
          tier2: 3 damage; vertical [slide](../../../movement/forced-movement.md) 4
          tier3: 4 damage; vertical [slide](../../../movement/forced-movement.md) 6; if this movement brings the target into contact with the ceiling, they are [restrained](../../../condition/restrained.md) (save ends).
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: No Escape
      target: Two creatures or objects
      type: feature
      usage: '-'
free_strike: 5
intuition: 1
keywords:
    - Elemental
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.fossil-cryptic.statblock/fossil-cryptic
    source: mcdm.monsters.v1
might: 3
movement: Burrow
name: Fossil Cryptic
organization: Solo
presence: 0
reason: 1
role: ""
size: 1L
speed: 8
stability: 3
stamina: "250"
type: statblock
```
