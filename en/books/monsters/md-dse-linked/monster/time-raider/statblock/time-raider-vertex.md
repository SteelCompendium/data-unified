---
agility: 1
ev: "10"
file_basename: time-raider-vertex
file_dpath: monster/time-raider/statblock
free_strike: 5
immunities:
    - Psychic 3
intuition: 1
item_id: time-raider-vertex
item_name: Time Raider Vertex
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 1
movement: Fly, hover
name: Time Raider Vertex
organization: Platoon
presence: 0
reason: 2
role: Support
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-vertex
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "62"
type: statblock
---

```ds-sb
agility: 1
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage, 2 psychic damage
          tier2: 7 damage, 3 psychic damage
          tier3: 9 damage, 4 psychic damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
      name: Psionic Slam
      target: One creature
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 2 cube within 10
      effects:
        - effect: '**Effect:** A portal fills the area, connecting to a location the vertex has experienced on any plane of existence, in person or otherwise. Any creature who enters the portal for the first time in a round or starts their turn there is instantly [teleported](../../../movement/teleport.md) to any unoccupied space in the portal at the chosen location. The portal lasts until the vertex uses this ability again, dismisses the portal (no action required), or is transported by the portal.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
      name: Split Space
      target: Special
      type: feature
      usage: Main action
    - distance: 4 burst
      effects:
        - effect: '**Effect:** Each target [shifts](../../../movement/shifting.md) up to half their speed.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: Invigorated March
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The vertex doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 5
immunities:
    - Psychic 3
intuition: 1
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-vertex
    source: mcdm.monsters.v1
might: 1
movement: Fly, hover
name: Time Raider Vertex
organization: Platoon
presence: 0
reason: 2
role: Support
size: "2"
speed: 5
stability: 2
stamina: "62"
type: statblock
```
