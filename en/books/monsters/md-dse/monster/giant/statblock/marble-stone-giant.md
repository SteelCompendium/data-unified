---
agility: 3
ev: "40"
file_basename: marble-stone-giant
file_dpath: monster/giant/statblock
free_strike: 8
intuition: 3
item_id: marble-stone-giant
item_name: Marble Stone Giant
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Marble Stone Giant
organization: Elite
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.giant.statblock/marble-stone-giant
size: "4"
source: mcdm.monsters.v1
speed: 6
stability: 10
stamina: "207"
type: statblock
---

```ds-sb
agility: 3
ev: "40"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 15
      effects:
        - roll: Power Roll + 4
          tier1: 6 damage; I < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: 10 damage; I < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 14 damage; I < 4 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Marble From a Great Sling
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: Vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
          tier2: Vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10
          tier3: Vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 12
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
      name: Far Flung
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 10 x 2 line within 1
      effects:
        - effect: '**Effect:** The ground in the area becomes slick and glossy. Any non-giant who starts or ends their turn in the area is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) and [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 squares.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Polish Stone Shape
      target: Special
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The marble stone giant takes damage.
            **Effect:** The marble stone giant halves the damage, and has damage weakness 3 and a +3 bonus to speed until the end of the encounter. The damage weakness increases by 3 each time the marble stone giant uses this ability in the same encounter.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Break Armor
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever an enemy obtains a tier 1 outcome on a melee ability used against the marble stone giant, they take a bane on that ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Stonebreaker Flesh
      type: feature
    - effects:
        - effect: The marble stone giant ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      feature_type: trait
      icon: ⭐️
      name: Stone Steps
      type: feature
    - effects:
        - effect: The marble stone giant can [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) through stone, but can't drag other creatures underground when they do so.
      feature_type: trait
      icon: ⭐️
      name: Stone Swim
      type: feature
free_strike: 8
intuition: 3
keywords:
    - Giant
    - Stone Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/marble-stone-giant
    source: mcdm.monsters.v1
might: 4
movement: Burrow
name: Marble Stone Giant
organization: Elite
presence: 0
reason: 0
role: Hexer
size: "4"
speed: 6
stability: 10
stamina: "207"
type: statblock
```
