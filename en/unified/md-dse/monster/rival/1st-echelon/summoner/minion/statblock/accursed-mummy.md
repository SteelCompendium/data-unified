---
agility: -1
cost: 3 Malice for three minions
cost_amount: "3"
cost_resource: Malice for three minions
file_basename: accursed-mummy
file_dpath: monster/rival/1st-echelon/summoner/minion/statblock
free_strike: 3
free_strike_damage_type: Poison
immunities:
    - Corruption 2
    - poison 2
intuition: 3
item_id: accursed-mummy
item_name: Accursed Mummy
keywords:
    - Mummy
    - Undead
might: 2
movement: —
name: Accursed Mummy
organization: Minion
presence: -1
reason: 1
role: Hexer
scc: mcdm.summoner.v1/monster.rival.1st-echelon.summoner.minion.statblock/accursed-mummy
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: 4 | 4 | 4
type: statblock
weaknesses:
    - Fire 1
---

```ds-sb
agility: -1
cost: 3 Malice for three minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: 2d10 + 3
          tier1: 3 poison damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 4 poison damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 6 poison damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fetid Bindings
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the mummy takes damage, each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the mummy takes 2 poison damage.
      feature_type: trait
      icon: ⭐️
      name: Mummy Dust
      type: feature
free_strike: 3
immunities:
    - Corruption 2
    - poison 2
intuition: 3
keywords:
    - Mummy
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.1st-echelon.summoner.minion.statblock/accursed-mummy
    source: mcdm.summoner.v1
might: 2
movement: —
name: Accursed Mummy
organization: Minion
presence: -1
reason: 1
role: Hexer
size: 1M
speed: 5
stability: 2
stamina: 4 | 4 | 4
type: statblock
weaknesses:
    - Fire 1
```
