---
agility: 1
ev: "16"
file_basename: bugbear-commander
file_dpath: monster/bugbear/statblock
free_strike: 5
intuition: 0
item_id: bugbear-commander
item_name: Bugbear Commander
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 2
name: Bugbear Commander
organization: Elite
presence: 0
reason: 2
role: Support
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-commander
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "80"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 10 damage
          tier3: 13 damage; one target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Inspiring Swordplay
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 8
      effects:
        - effect: '**Effect:** The target moves up to their speed and uses a signature ability.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: You Next!
      target: One ally
      type: feature
      usage: Main Action
    - cost: 5 Malice
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, then can use the Throw maneuver.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Fall Back!
      target: Each ally in the area
      type: feature
      usage: Main Action
    - distance: Melee 1
      effects:
        - effect: |-
            **Special:** The target must be [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the commander.
            **Effect:** The target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 4 squares. An ally doesn't take damage from being [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) this way.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
      name: Throw
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A size 1 creature or object is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) within distance, or a size 1 ally willingly moves within distance.
            **Effect:** The target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the commander.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Catcher
      target: The triggering creature or object
      type: feature
      usage: Free triggered action
    - effects:
        - effect: Any ally who has line of effect to the commander can end one condition on themself at the start of each of their turns.
      feature_type: trait
      icon: ⭐️
      name: The Commander's Watching
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-commander
    source: mcdm.monsters.v1
might: 2
name: Bugbear Commander
organization: Elite
presence: 0
reason: 2
role: Support
size: 1L
speed: 5
stability: 0
stamina: "80"
type: statblock
```
