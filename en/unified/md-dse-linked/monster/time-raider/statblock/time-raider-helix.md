---
agility: 2
ev: "10"
file_basename: time-raider-helix
file_dpath: monster/time-raider/statblock
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
item_id: time-raider-helix
item_name: Time Raider Helix
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 0
movement: Fly
name: Time Raider Helix
organization: Platoon
presence: 2
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-helix
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 corruption damage; [push](../../../movement/forced-movement.md) 2
          tier2: 8 corruption damage; [push](../../../movement/forced-movement.md) 4
          tier3: 11 corruption damage; [push](../../../movement/forced-movement.md) 6, [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
        - Weapon
      name: Blaster Volley
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 4 x 2 line within 10
      effects:
        - effect: |-
            **Effect:** The area is a psionically charged treadmill that pushes creatures and objects at high speed in one direction of the helix's choice. Any creature who enters the area or starts their turn there [slides](../../../movement/forced-movement.md) 3 squares toward the end of the area in the chosen direction. Each enemy in the area when it first appears takes 3 damage before they slide.
            **3 [Malice](../../../rule/monster/malice.md):** The helix creates a second kinetic lane.
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
      name: Kinetic Lane
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: The helix doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-helix
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: Time Raider Helix
organization: Platoon
presence: 2
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "40"
type: statblock
```
