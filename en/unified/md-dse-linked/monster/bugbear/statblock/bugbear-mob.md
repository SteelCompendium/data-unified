---
agility: -1
ev: 7 for four minions
file_basename: bugbear-mob
file_dpath: monster/bugbear/statblock
free_strike: 3
intuition: 1
item_id: bugbear-mob
item_name: Bugbear Mob
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 5
might: 3
name: Bugbear Mob
organization: Minion
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-mob
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "10"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: -1
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage; pull 2
          tier2: 6 damage; pull 3
          tier3: 7 damage; pull 4, [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Mug and Tear
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The mob can move through spaces as if they were a size 1L creature, and can occupy other creatures' spaces. At the start of each of the mob's turns, they can make a [free strike](../../../feature/common/main-actions/free-strike.md) against each creature whose space they share.
      feature_type: trait
      icon: ⭐️
      name: Swarm
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-mob
    source: mcdm.monsters.v1
might: 3
name: Bugbear Mob
organization: Minion
presence: 0
reason: 0
role: Brute
size: "3"
speed: 6
stability: 2
stamina: "10"
type: statblock
with_captain: +2 damage bonus to strikes
```
