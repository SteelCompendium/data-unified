---
agility: 4
ev: 10 for four minions
file_basename: minotaur-lackey
file_dpath: monster/minotaur/statblock
free_strike: 3
intuition: 1
item_id: minotaur-lackey
item_name: Minotaur Lackey
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 8
might: 3
name: Minotaur Lackey
organization: Minion
presence: -1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-lackey
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "13"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 4
ev: 10 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 3 damage
          tier2: 6 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 8 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Horn Vault
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The lackey can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
      feature_type: trait
      icon: ⭐️
      name: Minotaur Sense
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-lackey
    source: mcdm.monsters.v1
might: 3
name: Minotaur Lackey
organization: Minion
presence: -1
reason: 0
role: Harrier
size: "2"
speed: 8
stability: 2
stamina: "13"
type: statblock
with_captain: +2 bonus to speed
```
