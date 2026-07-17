---
agility: 1
ev: "9"
file_basename: dirt-mournling
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: dirt-mournling
item_name: Dirt Mournling
keywords:
    - Undead
level: 7
might: 4
movement: Burrow, climb
name: Dirt Mournling
organization: Horde
presence: -3
reason: -2
role: Controller
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/dirt-mournling
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: "64"
type: statblock
---

```ds-sb
agility: 1
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
          tier2: 10 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
          tier3: 11 damage; [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Mudslide
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 4
          tier1: 3 corruption damage; I < 2 [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 6 corruption damage; I < 3 [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 7 corruption damage; I < 4 [frightened](../../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Mourning Cry
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The first time the mournling is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 15 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Arise
      type: feature
    - effects:
        - effect: The mournling's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Immutable Form
      type: feature
    - effects:
        - effect: Whenever the mournling uses the Dig maneuver to breach the surface, they make a [free strike](../../../../feature/common/main-actions/free-strike.md) against each [adjacent](../../../../rule/combat/adjacent.md) enemy.
      feature_type: trait
      icon: ⭐️
      name: Rupture
      type: feature
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
keywords:
    - Undead
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/dirt-mournling
    source: mcdm.monsters.v1
might: 4
movement: Burrow, climb
name: Dirt Mournling
organization: Horde
presence: -3
reason: -2
role: Controller
size: "3"
speed: 6
stability: 3
stamina: "64"
type: statblock
```
