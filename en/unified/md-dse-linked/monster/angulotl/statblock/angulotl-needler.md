---
agility: 2
ev: "3"
file_basename: angulotl-needler
file_dpath: monster/angulotl/statblock
free_strike: 2
immunities:
    - Poison 2
intuition: 0
item_id: angulotl-needler
item_name: Angulotl Needler
keywords:
    - Angulotl
    - Humanoid
level: 1
might: 0
movement: Climb, swim
name: Angulotl Needler
organization: Horde
presence: -1
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-needler
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 4 poison damage
          tier2: 6 poison damage
          tier3: 7 poison damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Blowgun
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an adjacent enemy [grabs](../../../feature/common/maneuvers/grab.md) the needler or uses a melee ability against them, that enemy takes 2 poison damage.
      feature_type: trait
      icon: ⭐️
      name: Toxiferous
      type: feature
free_strike: 2
immunities:
    - Poison 2
intuition: 0
keywords:
    - Angulotl
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-needler
    source: mcdm.monsters.v1
might: 0
movement: Climb, swim
name: Angulotl Needler
organization: Horde
presence: -1
reason: 1
role: Artillery
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
```
