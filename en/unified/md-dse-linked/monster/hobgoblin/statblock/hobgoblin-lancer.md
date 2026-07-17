---
agility: 3
ev: 6 for four minions
file_basename: hobgoblin-lancer
file_dpath: monster/hobgoblin/statblock
free_strike: 2
immunities:
    - Fire 2
intuition: 2
item_id: hobgoblin-lancer
item_name: Hobgoblin Lancer
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 1
name: Hobgoblin Lancer
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-lancer
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2 or ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 2 corruption damage
          tier2: 4 corruption damage; [push](../../../movement/forced-movement.md) 1
          tier3: 6 corruption damage; [push](../../../movement/forced-movement.md) 2
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Grim Thrust
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the lancer is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the lancer takes 2 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 2
immunities:
    - Fire 2
intuition: 2
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-lancer
    source: mcdm.monsters.v1
might: 1
name: Hobgoblin Lancer
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 damage bonus to strikes
```
