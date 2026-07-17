---
agility: 2
ev: 3 for 4 minions
file_basename: angulotl-cleaver
file_dpath: monster/angulotl/statblock
free_strike: 2
immunities:
    - Poison 2
intuition: 1
item_id: angulotl-cleaver
item_name: Angulotl Cleaver
keywords:
    - Angulotl
    - Humanoid
level: 1
might: 0
movement: Climb, swim
name: Angulotl Cleaver
organization: Minion
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-cleaver
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
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
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Hop and Chop
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an adjacent enemy [grabs](../../../feature/common/maneuvers/grab.md) the cleaver or uses a melee ability against them, that enemy takes 1 poison damage.
      feature_type: trait
      icon: ⭐️
      name: Toxiferous
      type: feature
free_strike: 2
immunities:
    - Poison 2
intuition: 1
keywords:
    - Angulotl
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-cleaver
    source: mcdm.monsters.v1
might: 0
movement: Climb, swim
name: Angulotl Cleaver
organization: Minion
presence: 0
reason: 0
role: Ambusher
size: 1S
speed: 6
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
```
