---
agility: 1
ev: "12"
file_basename: hobgoblin-burning-witch
file_dpath: monster/hobgoblin/statblock
free_strike: 5
immunities:
    - Fire 4
intuition: 2
item_id: hobgoblin-burning-witch
item_name: Hobgoblin Burning Witch
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 0
movement: Teleport
name: Hobgoblin Burning Witch
organization: Platoon
presence: 3
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-burning-witch
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 1
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 4 corruption or fire damage
          tier2: 6 corruption or fire damage
          tier3: 8 corruption or fire damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Soul Burn
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target can [teleport](../../../movement/teleport.md) up to 5 squares. Each creature [adjacent](../../../rule/combat/adjacent.md) to a target at their destination takes 3 fire damage.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Burning Legion
      target: Three creatures
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the burning witch is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the burning witch takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 5
immunities:
    - Fire 4
intuition: 2
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-burning-witch
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: Hobgoblin Burning Witch
organization: Platoon
presence: 3
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "50"
type: statblock
```
