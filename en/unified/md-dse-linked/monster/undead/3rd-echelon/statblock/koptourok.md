---
agility: 2
ev: "9"
file_basename: koptourok
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: koptourok
item_name: Koptourok
keywords:
    - Undead
level: 7
might: 4
name: Koptourok
organization: Horde
presence: -1
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/koptourok
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 5
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; M < 2 [grabbed](../../../../condition/grabbed.md)
          tier2: 10 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
          tier3: 11 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Choking Grasp
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 burst
      effects:
        - roll: Power Roll + 4
          tier1: '[Pull](../../../../movement/forced-movement.md) 3; M < 2 5 corruption damage'
          tier2: '[Pull](../../../../movement/forced-movement.md) 5; M < 3 5 corruption damage'
          tier3: '[Pull](../../../../movement/forced-movement.md) 7; M < 4 5 corruption damage'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Inhale
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The first time the koptourok is made [winded](../../../../rule/health/winded.md) by damage that isn't fire damage or holy damage, each enemy within 3 squares of them takes 8 corruption damage. Any enemy who takes this damage and has M < 3 is also [weakened](../../../../condition/weakened.md) (save ends)
      feature_type: trait
      icon: ⭐️
      name: Exhale
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
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/koptourok
    source: mcdm.monsters.v1
might: 4
name: Koptourok
organization: Horde
presence: -1
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 1
stamina: "40"
type: statblock
```
