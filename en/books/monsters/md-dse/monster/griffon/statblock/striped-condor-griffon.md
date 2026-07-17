---
agility: 2
ev: "16"
file_basename: striped-condor-griffon
file_dpath: monster/griffon/statblock
free_strike: 5
intuition: 2
item_id: striped-condor-griffon
item_name: Striped Condor Griffon
keywords:
    - Beast
    - Griffon
level: 2
might: 2
movement: Fly
name: Striped Condor Griffon
organization: Elite
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.griffon.statblock/striped-condor-griffon
size: "3"
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "100"
type: statblock
---

```ds-sb
agility: 2
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 11 damage; one target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 2 squares; the other target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 2 squares
          tier3: 14 damage; one target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 2 squares and knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone); the other target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Violent Thrashing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The griffon [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed along the ground in straight line. Each enemy who comes [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the griffon during this shift can choose to either take 5 damage or be knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Bound Ahead
      target: Self
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 x 3 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 0 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical'
          tier2: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 1 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical'
          tier3: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6; M < 2 the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) is vertical'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Power Wing Buffet
      target: Each creature or object in the area
      type: feature
      usage: Maneuver
    - distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** The griffon flies directly above a creature within distance.
            **Effect:** The griffon dives down onto the target, taking no damage from falling if they reach the ground. The target takes 3 damage for each square the griffon dove, and if they have A < 2, they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Circle and Strike
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the griffon, a creature has a double bane on the Escape Grab maneuver.
      feature_type: trait
      icon: ⭐️
      name: Beast of Prey
      type: feature
    - effects:
        - effect: Any power roll that could knock the griffon [prone](scc.v1:mcdm.heroes.v1/condition/prone) takes a bane.
      feature_type: trait
      icon: ⭐️
      name: Steady
      type: feature
    - effects:
        - effect: The griffon can attempt hide even while observed. Additionally, while no enemy has line of effect to them, the griffon can attempt to hide at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Banded Predator
      type: feature
free_strike: 5
intuition: 2
keywords:
    - Beast
    - Griffon
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.griffon.statblock/striped-condor-griffon
    source: mcdm.monsters.v1
might: 2
movement: Fly
name: Striped Condor Griffon
organization: Elite
presence: 1
reason: -1
role: Brute
size: "3"
speed: 7
stability: 3
stamina: "100"
type: statblock
```
