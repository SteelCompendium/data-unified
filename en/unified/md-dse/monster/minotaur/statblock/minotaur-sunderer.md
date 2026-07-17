---
agility: 1
ev: "20"
file_basename: minotaur-sunderer
file_dpath: monster/minotaur/statblock
free_strike: 6
intuition: 2
item_id: minotaur-sunderer
item_name: Minotaur Sunderer
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
might: 2
name: Minotaur Sunderer
organization: Elite
presence: -1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-sunderer
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 1
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 12 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 15 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Spiked Maul
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: I < 0 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
          tier2: I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
          tier3: I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Fearsome Bay
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; M < 0 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 8 damage; M < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 9 damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Disemboweling Horns
      target: One creature
      type: feature
      usage: Maneuver
    - distance: Ranged 6
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the sunderer.
            **Effect:** The sunderer uses the Charge main action and Spiked Maul against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Retaliatory Strike
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: The sunderer can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
      feature_type: trait
      icon: ⭐️
      name: Minotaur Sense
      type: feature
free_strike: 6
intuition: 2
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-sunderer
    source: mcdm.monsters.v1
might: 2
name: Minotaur Sunderer
organization: Elite
presence: -1
reason: 0
role: Brute
size: "2"
speed: 6
stability: 2
stamina: "120"
type: statblock
```
