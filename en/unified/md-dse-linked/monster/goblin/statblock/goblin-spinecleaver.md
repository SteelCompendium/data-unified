---
agility: 0
ev: 3 for four minions
file_basename: goblin-spinecleaver
file_dpath: monster/goblin/statblock
free_strike: 2
intuition: 0
item_id: goblin-spinecleaver
item_name: Goblin Spinecleaver
keywords:
    - Goblin
    - Humanoid
level: 1
might: 2
movement: Climb
name: Goblin Spinecleaver
organization: Minion
presence: -1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-spinecleaver
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 0
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 4 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 5 damage; [push](../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Axe
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The spinecleaver doesn't provoke [opportunity attacks](../../../rule/combat/opportunity-attack.md) by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Goblin
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-spinecleaver
    source: mcdm.monsters.v1
might: 2
movement: Climb
name: Goblin Spinecleaver
organization: Minion
presence: -1
reason: 0
role: Brute
size: 1S
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: +1 damage bonus to strikes
```
