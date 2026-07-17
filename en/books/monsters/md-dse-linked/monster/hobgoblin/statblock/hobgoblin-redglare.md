---
agility: 2
ev: "16"
file_basename: hobgoblin-redglare
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 6
intuition: 3
item_id: hobgoblin-redglare
item_name: Hobgoblin Redglare
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
might: 0
movement: Teleport
name: Hobgoblin Redglare
organization: Platoon
presence: 3
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-redglare
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "70"
type: statblock
---

```ds-sb
agility: 2
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 9 corruption damage; P < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 14 corruption damage; P < 2 [restrained](../../../condition/restrained.md) (save ends)
          tier3: 17 corruption damage; P < 3 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Eye Flash
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 10 corruption damage
          tier2: 10 corruption damage, or if the target has P < 2 they are judged
          tier3: The target is judged.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Glare of the Old Judgments
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: When the redglare is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the redglare takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 6
immunities:
    - Fire 6
intuition: 3
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-redglare
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: Hobgoblin Redglare
organization: Platoon
presence: 3
reason: 2
role: Hexer
size: 1L
speed: 5
stability: 4
stamina: "70"
type: statblock
```
