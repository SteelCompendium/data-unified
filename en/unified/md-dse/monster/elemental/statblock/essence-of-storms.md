---
agility: 2
ev: "20"
file_basename: essence-of-storms
file_dpath: monster/elemental/statblock
free_strike: 5
immunities:
    - Lightning 5
intuition: 0
item_id: essence-of-storms
item_name: Essence of Storms
keywords:
    - Elemental
level: 3
might: 1
movement: Fly
name: Essence of Storms
organization: Elite
presence: 2
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.elemental.statblock/essence-of-storms
size: 1S
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "100"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: 1 burst
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage
          tier2: 5 damage, 4 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 5 damage, 7 lightning damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Bluster
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: |-
            **Effect:** Until the start of the essence's next turn, the target has lightning immunity 5.
            **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Until the end of the encounter, a vortex surrounds the target in a 3 aura. The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. Additionally, at the end of each of the target's turns, they can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature in the area up to 5 squares.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Convocation of Squalls
      target: Self or one elemental
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the essence.
            **Effect:** The target takes 5 lightning damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Thunderclap
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: The essence can't be [restrained](scc.v1:mcdm.heroes.v1/condition/restrained), [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone), and they ignore [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      feature_type: trait
      icon: ⭐️
      name: Fickle and Free
      type: feature
free_strike: 5
immunities:
    - Lightning 5
intuition: 0
keywords:
    - Elemental
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elemental.statblock/essence-of-storms
    source: mcdm.monsters.v1
might: 1
movement: Fly
name: Essence of Storms
organization: Elite
presence: 2
reason: -1
role: Harrier
size: 1S
speed: 8
stability: 0
stamina: "100"
type: statblock
```
