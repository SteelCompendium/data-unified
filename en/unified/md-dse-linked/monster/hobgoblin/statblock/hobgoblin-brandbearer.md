---
agility: 1
ev: 6 for four minions
file_basename: hobgoblin-brandbearer
file_dpath: monster/hobgoblin/statblock
free_strike: 2
immunities:
    - Fire 2
intuition: 0
item_id: hobgoblin-brandbearer
item_name: Hobgoblin Brandbearer
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 0
name: Hobgoblin Brandbearer
organization: Minion
presence: 3
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-brandbearer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 1
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 2 fire damage
          tier2: 4 fire damage; M < 2 fire weakness 5 (save ends)
          tier3: 6 fire damage; M < 3 fire weakness 5 (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Searing Grasp
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an enemy takes fire damage, they take 1 extra fire damage for each brandbearer [adjacent](../../../rule/combat/adjacent.md) to them.
      feature_type: trait
      icon: ⭐️
      name: Open Furnace
      type: feature
    - effects:
        - effect: When the brandbearer is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the brandbearer takes 2 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 2
immunities:
    - Fire 2
intuition: 0
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-brandbearer
    source: mcdm.monsters.v1
might: 0
name: Hobgoblin Brandbearer
organization: Minion
presence: 3
reason: 2
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: Gain an edge on strikes
```
