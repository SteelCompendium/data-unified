---
agility: 1
ev: "40"
file_basename: granite-stone-giant
file_dpath: monster/giant/statblock
free_strike: 8
intuition: 2
item_id: granite-stone-giant
item_name: Granite Stone Giant
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Granite Stone Giant
organization: Elite
presence: 1
reason: 1
role: Defender
scc: mcdm.monsters.v1/monster.giant.statblock/granite-stone-giant
size: "4"
source: mcdm.monsters.v1
speed: 7
stability: 10
stamina: "247"
type: statblock
---

```ds-sb
agility: 1
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage
          tier2: 17 damage; R < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 21 damage; R < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Jagged Stone Club
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 2 burst
      effects:
        - roll: Power Roll + 4
          tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier3: 14 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Crag Burst
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The granite stone giant moves up to their speed and creates a 14 wall of stone in squares [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the path of their movement.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Castle Stone Shape
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 3
      effects:
        - effect: |-
            **Trigger:** A creature or object within distance moves or [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) away from the granite stone giant.
            **Effect:** A 1-square pillar of stone rises 5 squares out of the ground beneath the target, who moves with the ground to its new elevation, then is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Pillar
      target: The triggering creature or object
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever an enemy obtains a tier 1 outcome on a melee ability used against the granite stone giant, they take a bane on that ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Stonebreaker Flesh
      type: feature
    - effects:
        - effect: The granite stone giant ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      feature_type: trait
      icon: ⭐️
      name: Stone Steps
      type: feature
    - effects:
        - effect: The granite stone giant can [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) through stone, but can't drag other creatures underground when they do so.
      feature_type: trait
      icon: ⭐️
      name: Stone Swim
      type: feature
free_strike: 8
intuition: 2
keywords:
    - Giant
    - Stone Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/granite-stone-giant
    source: mcdm.monsters.v1
might: 4
movement: Burrow
name: Granite Stone Giant
organization: Elite
presence: 1
reason: 1
role: Defender
size: "4"
speed: 7
stability: 10
stamina: "247"
type: statblock
```
