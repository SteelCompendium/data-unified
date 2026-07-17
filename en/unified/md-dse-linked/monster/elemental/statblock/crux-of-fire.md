---
agility: 2
ev: "20"
file_basename: crux-of-fire
file_dpath: monster/elemental/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 1
item_id: crux-of-fire
item_name: Crux of Fire
keywords:
    - Elemental
level: 3
might: -1
name: Crux of Fire
organization: Elite
presence: 2
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.elemental.statblock/crux-of-fire
size: 1T
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "80"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Ranged 12
      effects:
        - roll: Power Roll + 2
          tier1: 8 fire damage
          tier2: 12 fire damage; A < 1 the target is burning (save ends)
          tier3: 15 fire damage; A < 2 the target is burning (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Spitfire
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: |-
            **Effect:** Until the start of the crux's next turn, the target has fire immunity 5.
            **3 [Malice](../../../rule/monster/malice.md):** Until the end of the encounter, the ground within 3 squares of the target is wreathed in fire. Any enemy who enters that area for the first time in a round or starts their turn there takes 3 fire damage.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Convocation of Flames
      target: Self or one elemental
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The crux takes damage.
            **Effect:** The crux ignores any effects associated with the damage and can [fly](../../../movement/fly.md) up to their speed. If the crux doesn't end this movement on solid ground, they fall.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: Flame Jet
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: The crux can't be [restrained](../../../condition/restrained.md), [slowed](../../../condition/slowed.md), or knocked [prone](../../../condition/prone.md), and they ignore [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Fickle and Free
      type: feature
free_strike: 6
immunities:
    - Fire 5
intuition: 1
keywords:
    - Elemental
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elemental.statblock/crux-of-fire
    source: mcdm.monsters.v1
might: -1
name: Crux of Fire
organization: Elite
presence: 2
reason: 0
role: Artillery
size: 1T
speed: 6
stability: 0
stamina: "80"
type: statblock
```
