---
agility: 2
ev: 3 for 4 minions
file_basename: clawfish
file_dpath: monster/angulotl/statblock
free_strike: 2
immunities:
    - Lightning 3
    - Poison 2
intuition: -2
item_id: clawfish
item_name: Clawfish
keywords:
    - Angulotl
    - Animal
level: 1
might: 0
movement: Climb, swim
name: Clawfish
organization: Minion
presence: 1
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.angulotl.statblock/clawfish
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage; [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Hookclaw
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: At the start of each of their turns, the clawfish deals 2 lightning damage to each wet enemy within 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Shocking
      type: feature
free_strike: 2
immunities:
    - Lightning 3
    - Poison 2
intuition: -2
keywords:
    - Angulotl
    - Animal
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.angulotl.statblock/clawfish
    source: mcdm.monsters.v1
might: 0
movement: Climb, swim
name: Clawfish
organization: Minion
presence: 1
reason: -3
role: Brute
size: 1S
speed: 5
stability: 0
stamina: "5"
type: statblock
with_captain: Gain an edge on strikes
```
