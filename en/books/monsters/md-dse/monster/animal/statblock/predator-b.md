---
agility: 1
ev: "16"
file_basename: predator-b
file_dpath: monster/animal/statblock
free_strike: 5
intuition: 1
item_id: predator-b
item_name: Predator B
keywords:
    - Animal
level: 3
might: 2
name: Predator B
organization: Elite
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.animal.statblock/predator-b
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "100"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Natural Weapon
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 1 burst
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 6 damage
          tier3: 8 damage; A < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Wild Swing
      target: Each enemy or object in the area
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature or object within distance deals damage to the predator.
            **Effect:** The target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 5 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Swat
      target: The triggering creature or object
      type: feature
      usage: Triggered action
    - effects:
        - effect: The predator can move through enemies' and objects' spaces at their usual speed. Any mundane size 2 or smaller object whose space they move through is destroyed. When the predator enters a creature's space for the first time on a turn, that creature takes 3 damage.
      feature_type: trait
      icon: ⭐️
      name: Trample
      type: feature
    - effects:
        - effect: While outdoors or in a natural environment, the predator can negate a bane on their abilities or turn a double bane into a bane.
      feature_type: trait
      icon: ⭐️
      name: Nature's Spirit
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Animal
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.animal.statblock/predator-b
    source: mcdm.monsters.v1
might: 2
name: Predator B
organization: Elite
presence: 0
reason: -1
role: Brute
size: "3"
speed: 5
stability: 2
stamina: "100"
type: statblock
```
