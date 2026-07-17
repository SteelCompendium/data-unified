---
agility: 2
ev: "3"
file_basename: angulotl-slink
file_dpath: monster/angulotl/statblock
free_strike: 2
immunities:
    - Poison 2
intuition: 0
item_id: angulotl-slink
item_name: Angulotl Slink
keywords:
    - Angulotl
    - Humanoid
level: 1
might: 1
movement: Climb, swim
name: Angulotl Slink
organization: Horde
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-slink
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 6
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage; [pull](../../../movement/forced-movement.md) 2
          tier2: 6 damage; [pull](../../../movement/forced-movement.md) 4
          tier3: 7 damage; [pull](../../../movement/forced-movement.md) 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tonguelash
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The slink jumps up to 3 squares. If they have [cover](../../../rule/combat/cover.md) or [concealment](../../../rule/combat/concealment.md) when they land, they can attempt to hide.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Hop To It
      target: Self
      type: feature
      usage: Free maneuver
    - effects:
        - effect: The slink excretes a sticky residue into their square at the end of each of their turns. Any non-angulotl who enters or leaves the square is stuck, and must use a maneuver to break free or be [restrained](../../../condition/restrained.md) until the end of their turn. Objects are likewise affected, and a creature must use a maneuver to remove an object from the square.
      feature_type: trait
      icon: ⭐️
      name: Adhesive
      type: feature
    - effects:
        - effect: Whenever an adjacent enemy [grabs](../../../feature/common/maneuvers/grab.md) the slink or uses a melee ability against them, that enemy takes 2 poison damage.
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
    scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-slink
    source: mcdm.monsters.v1
might: 1
movement: Climb, swim
name: Angulotl Slink
organization: Horde
presence: 0
reason: 0
role: Ambusher
size: 1S
speed: 5
stability: 0
stamina: "15"
type: statblock
```
