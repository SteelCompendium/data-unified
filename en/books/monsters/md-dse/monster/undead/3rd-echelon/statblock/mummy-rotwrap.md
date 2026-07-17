---
agility: -2
ev: 9 for four minions
file_basename: mummy-rotwrap
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 4
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: mummy-rotwrap
item_name: Mummy Rotwrap
keywords:
    - Mummy
    - Undead
level: 7
might: 4
name: Mummy Rotwrap
organization: Minion
presence: -2
reason: -2
role: Brute
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/mummy-rotwrap
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "15"
type: statblock
weaknesses:
    - Fire 5
with_captain: +3 bonus to melee distance
---

```ds-sb
agility: -2
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 7 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fetid Wrappings
      target: One creature or object per minion
      type: feature
      usage: Main action
free_strike: 4
immunities:
    - Corruption 7
    - poison 7
intuition: 1
keywords:
    - Mummy
    - Undead
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/mummy-rotwrap
    source: mcdm.monsters.v1
might: 4
name: Mummy Rotwrap
organization: Minion
presence: -2
reason: -2
role: Brute
size: 1M
speed: 5
stability: 1
stamina: "15"
type: statblock
weaknesses:
    - Fire 5
with_captain: +3 bonus to melee distance
```
