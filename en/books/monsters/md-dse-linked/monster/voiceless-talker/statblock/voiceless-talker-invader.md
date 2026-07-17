---
agility: 1
ev: "32"
file_basename: voiceless-talker-invader
file_dpath: monster/voiceless-talker/statblock
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
item_id: voiceless-talker-invader
item_name: Voiceless Talker Invader
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Hover, teleport
name: Voiceless Talker Invader
organization: Elite
presence: 2
reason: 3
role: Controller
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/voiceless-talker-invader
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "140"
type: statblock
---

```ds-sb
agility: 1
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage
          tier2: 15 damage; M < 2 [grabbed](../../../condition/grabbed.md)
          tier3: 18 damage; M < 3 [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tentacle
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 3
          tier1: 6 psychic damage; R < 1 [push](../../../movement/forced-movement.md) 2
          tier2: 10 psychic damage; R < 2 [push](../../../movement/forced-movement.md) 3
          tier3: 12 psychic damage; R < 3 [push](../../../movement/forced-movement.md) 4 and [prone](../../../condition/prone.md)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: Psionic Boom
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 6 damage; vertical [slide](../../../movement/forced-movement.md) 2
          tier2: 10 damage; vertical [slide](../../../movement/forced-movement.md) 2
          tier3: 12 damage; vertical [slide](../../../movement/forced-movement.md) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
      name: Tentacle Toss
      target: One creature
      type: feature
      usage: Maneuver
    - distance: Special
      effects:
        - effect: |-
            **Trigger:** A creature [grabbed](../../../condition/grabbed.md) by the invader resists an ability's [potency](../../../rule/character/potency.md).
            **Effect:** The [potency](../../../rule/character/potency.md) increases by 2.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
        - Psionic
      name: Brain Drain
      target: The triggering creature
      type: feature
      usage: Triggered Action
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) voiceless talker within 5 squares of the invader uses a psionic ability, they can do so as if they were in the invader's space, and the ability has a double edge.
      feature_type: trait
      icon: ⭐️
      name: Psionic Amplifier
      type: feature
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Horror
    - Voiceless Talker
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/voiceless-talker-invader
    source: mcdm.monsters.v1
might: -1
movement: Hover, teleport
name: Voiceless Talker Invader
organization: Elite
presence: 2
reason: 3
role: Controller
size: 1M
speed: 5
stability: 2
stamina: "140"
type: statblock
```
