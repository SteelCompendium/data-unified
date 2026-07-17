---
agility: 1
ev: "32"
file_basename: hulking-brain
file_dpath: monster/voiceless-talker/statblock
free_strike: 7
intuition: -2
item_id: hulking-brain
item_name: Hulking Brain
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: 3
name: Hulking Brain
organization: Elite
presence: 0
reason: -2
role: Brute
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/hulking-brain
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "180"
type: statblock
---

```ds-sb
agility: 1
ev: "32"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage
          tier2: 10 damage; A < 2 [grabbed](../../../condition/grabbed.md)
          tier3: 11 damage; A < 3 [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Four-Way Grasp
      target: Four creatures or objects
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage; M < 1 3 damage
          tier2: 10 damage; M < 2 3 damage
          tier3: 13 damage; M < 3 6 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
      name: Cerebral Suplex
      target: Each enemy
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The hulking brain [shifts](../../../movement/shifting.md) up to 4 squares, ignoring difficu terrain.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Lumber
      target: Self
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** An ally voiceless talker within 5 squares takes damage from an enemy ability.
            **Effect:** The hulking brain [shifts](../../../movement/shifting.md) [adjacent](../../../rule/combat/adjacent.md) to the ally and becomes the new target of the ability.
            **2 Malice:** The enemy is knocked [prone](../../../condition/prone.md).
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Brawny Buffe
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The hulking brain can carry up to four size 1 creatures they have [grabbed](../../../condition/grabbed.md), and takes no penalty to their speed while doing so.
      feature_type: trait
      icon: ⭐️
      name: Biceps to Spare
      type: feature
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) voiceless talker within 5 squares of the hulking brain uses a psionic ability, they can do so as if they were in the hulking brain's space.
      feature_type: trait
      icon: ⭐️
      name: Psionic Conductor
      type: feature
free_strike: 7
intuition: -2
keywords:
    - Horror
    - Voiceless Talker
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/hulking-brain
    source: mcdm.monsters.v1
might: 3
name: Hulking Brain
organization: Elite
presence: 0
reason: -2
role: Brute
size: 1L
speed: 5
stability: 4
stamina: "180"
type: statblock
```
