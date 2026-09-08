---
agility: -2
ev: "12"
file_basename: bonecage
file_dpath: monster/undead/4th-echelon/statblock
free_strike: 4
immunities:
    - Corruption 10
    - poison 10
intuition: 3
item_id: bonecage
item_name: Bonecage
keywords:
    - Undead
    - Soulless
level: 10
might: 5
movement: Climb
name: Bonecage
organization: Horde
presence: -1
reason: -2
role: Controller
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/bonecage
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 5
stamina: "55"
type: statblock
---

```ds-sb
agility: -2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 5
          tier1: 9 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
          tier2: 12 damage; M < 5 [grabbed](../../../../condition/grabbed.md)
          tier3: 14 damage; [grabbed](../../../../condition/grabbed.md)
        - effect: The bonecage can have up to four [size](../../../../rule/character/size.md) 1 targets [grabbed](../../../../condition/grabbed.md) at once. Any creature [grabbed](../../../../condition/grabbed.md) by the bonecage takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../../feature/common/maneuvers/escape-grab.md) maneuver, and the bonecage has [damage immunity](../../../../rule/damage/damage-immunity.md) 5 against that creature's abilities. When the bonecage is [force moved](../../../../movement/forced-movement.md), any creature or object they have [grabbed](../../../../condition/grabbed.md) moves with them.
          name: Effect
        - cost: 3 Malice
          effect: While [grabbed](../../../../condition/grabbed.md) this way, a target can't [teleport](../../../../movement/teleport.md) or be [teleported](../../../../movement/teleport.md).
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Ribcage Chomp
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Four 10 x 1 lines within 3
      effects:
        - effect: The bonecage can put up to two 90-degree bends in each of the lines. Each target makes an Agility test.
          name: Effect
          tier1: 9 damage
          tier2: 7 damage
          tier3: 4 damage
        - effect: The area is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies. The effect ends at the end of the encounter or when the bonecage uses this ability again.
          name: Effect
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Labyrinth of Bone
      target: Each enemy in the area
      type: feature
      usage: Main action
free_strike: 4
immunities:
    - Corruption 10
    - poison 10
intuition: 3
keywords:
    - Undead
    - Soulless
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/bonecage
    source: mcdm.monsters.v1
might: 5
movement: Climb
name: Bonecage
organization: Horde
presence: -1
reason: -2
role: Controller
size: "3"
speed: 6
stability: 5
stamina: "55"
type: statblock
```
