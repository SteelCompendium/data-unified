---
agility: 2
ev: '-'
file_basename: bugbear-commando
file_dpath: monster/retainer/statblock
free_strike: 2
intuition: 1
item_id: bugbear-commando
item_name: Bugbear Commando
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 2
name: Bugbear Commando
organization: Retainer
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.retainer.statblock/bugbear-commando
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 5 damage
          tier2: 6 damage
          tier3: 11 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Bear Hug
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the commando.
            **Effect:** The target is vertical pushed up to 5 squares. An ally doesn't take damage from being [force moved](../../../movement/forced-movement.md) this way.
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
            **Trigger:** A size 1 creature or object is [force moved](../../../movement/forced-movement.md) within distance, or a size 1 ally willingly moves within distance.
            **Effect:** The target is [grabbed](../../../condition/grabbed.md) by the commando.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Catcher
      target: The triggering creature or object
      type: feature
      usage: Free triggered action
free_strike: 2
intuition: 1
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/bugbear-commando
    source: mcdm.monsters.v1
might: 2
name: Bugbear Commando
organization: Retainer
presence: 0
reason: 0
role: Ambusher
size: 1L
speed: 5
stability: 0
stamina: "30"
type: statblock
```
