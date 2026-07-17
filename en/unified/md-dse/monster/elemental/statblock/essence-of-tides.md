---
agility: 0
ev: "20"
file_basename: essence-of-tides
file_dpath: monster/elemental/statblock
free_strike: 5
immunities:
    - Cold 5
intuition: -1
item_id: essence-of-tides
item_name: Essence of Tides
keywords:
    - Elemental
level: 3
might: 2
movement: Swim
name: Essence of Tides
organization: Elite
presence: 2
reason: 1
role: Controller
scc: mcdm.monsters.v1/monster.elemental.statblock/essence-of-tides
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "80"
type: statblock
---

```ds-sb
agility: 0
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 11 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 14 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Water Wing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: |-
            **Effect:** Until the start of the essence's next turn, the target has cold immunity 5.
            **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Until the end of the encounter, the ground within 1 square of the target is a pool of water that is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). This water extends out behind the target as they move, creating a stream that lasts until the end of the encounter. Any enemy who ends their turn in the stream and has M < 2 is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Convocation of Waves
      target: Self or one elemental
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals rolled damage to the target.
            **Effect:** The essence makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Sea-Salted Wounds
      target: One enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: The essence can't be [restrained](scc.v1:mcdm.heroes.v1/condition/restrained), [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone), and they ignore [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      feature_type: trait
      icon: ⭐️
      name: Fickle and Free
      type: feature
    - effects:
        - effect: Whenever the essence starts their turn in a space containing water, they can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the end of their turn. While flying, the essence doesn't provoke opportunity attacks.
      feature_type: trait
      icon: ⭐️
      name: Water Glide
      type: feature
free_strike: 5
immunities:
    - Cold 5
intuition: -1
keywords:
    - Elemental
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elemental.statblock/essence-of-tides
    source: mcdm.monsters.v1
might: 2
movement: Swim
name: Essence of Tides
organization: Elite
presence: 2
reason: 1
role: Controller
size: 1M
speed: 7
stability: 1
stamina: "80"
type: statblock
```
