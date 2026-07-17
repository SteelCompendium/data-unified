---
agility: 2
ev: 3 for four minions
file_basename: goblin-sniper
file_dpath: monster/goblin/statblock
free_strike: 2
intuition: 0
item_id: goblin-sniper
item_name: Goblin Sniper
keywords:
    - Goblin
    - Humanoid
level: 1
might: -2
movement: Climb
name: Goblin Sniper
organization: Minion
presence: -1
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-sniper
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Bow
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The sniper doesn't provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving.
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
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-sniper
    source: mcdm.monsters.v1
might: -2
movement: Climb
name: Goblin Sniper
organization: Minion
presence: -1
reason: 0
role: Artillery
size: 1S
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
```
