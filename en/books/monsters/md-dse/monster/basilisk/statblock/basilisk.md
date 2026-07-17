---
agility: 0
ev: "12"
file_basename: basilisk
file_dpath: monster/basilisk/statblock
free_strike: 5
immunities:
    - Poison 4
intuition: -1
item_id: basilisk
item_name: Basilisk
keywords:
    - Basilisk
    - Beast
level: 1
might: 2
name: Basilisk
organization: Elite
presence: -1
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "80"
type: statblock
---

```ds-sb
agility: 0
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 poison damage
          tier2: 10 poison damage
          tier3: 13 poison damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Noxious Bite
      target: Two creatures or objects
      type: feature
      usage: Main Action
    - distance: 5 x 2 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: M < 0 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: M < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: '[Slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends); or if M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Petrifying Eye Beams
      target: Special
      type: feature
      usage: Maneuver
    - cost: 5 Malice
      distance: 3 cube within 1
      effects:
        - roll: Power Roll + 2
          tier1: 4 poison damage; M < 0 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier2: 6 poison damage; M < 1 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 9 poison damage; M < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Poison Fumes
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: 1 burst
      effects:
        - effect: |-
            **Trigger:** The basilisk takes damage from a melee ability.
            **Effect:** Each target takes 5 damage. Any target who has A < 2 is also [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Lash Out
      target: Each enemy in the area
      type: feature
      usage: Triggered action
    - effects:
        - effect: The area within 3 squares of the basilisk is difficult terrain for enemies.
      feature_type: trait
      icon: ⭐️
      name: Calcifying Presence
      type: feature
free_strike: 5
immunities:
    - Poison 4
intuition: -1
keywords:
    - Basilisk
    - Beast
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk
    source: mcdm.monsters.v1
might: 2
name: Basilisk
organization: Elite
presence: -1
reason: -3
role: Brute
size: "2"
speed: 8
stability: 2
stamina: "80"
type: statblock
```
