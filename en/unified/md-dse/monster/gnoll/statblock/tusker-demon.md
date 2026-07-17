---
agility: -1
ev: "16"
file_basename: tusker-demon
file_dpath: monster/gnoll/statblock
free_strike: 5
intuition: 0
item_id: tusker-demon
item_name: Tusker Demon
keywords:
    - Abyssal
    - Demon
    - Gnoll
level: 2
might: 2
name: Tusker Demon
organization: Elite
presence: -1
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.gnoll.statblock/tusker-demon
size: "3"
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "100"
type: statblock
---

```ds-sb
agility: -1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Gore
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 7
      effects:
        - effect: |-
            **Trigger:** An enemy within distance deals damage to the tusker.
            **Effect:** The tusker demon uses the Charge main action and Gore against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Vengeful Tusker
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: The tusker demon can move through enemies' spaces at their usual speed. When the tusker enters a creature's space for the first time on a turn, that creature takes 5 damage. The tusker demon can end their turn in a [prone](scc.v1:mcdm.heroes.v1/condition/prone) size 1 creature's space, preventing the creature from standing up.
      feature_type: trait
      icon: ⭐️
      name: Trample
      type: feature
    - effects:
        - effect: While the tusker demon is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an edge on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Abyssal
    - Demon
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.gnoll.statblock/tusker-demon
    source: mcdm.monsters.v1
might: 2
name: Tusker Demon
organization: Elite
presence: -1
reason: -3
role: Brute
size: "3"
speed: 7
stability: 3
stamina: "100"
type: statblock
```
