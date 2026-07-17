---
agility: 1
ev: "6"
file_basename: flesh-mournling
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 2
item_id: flesh-mournling
item_name: Flesh Mournling
keywords:
    - Undead
level: 4
might: 3
name: Flesh Mournling
organization: Horde
presence: -1
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/flesh-mournling
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "35"
type: statblock
---

```ds-sb
agility: 1
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage
          tier2: 7 damage
          tier3: 9 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Multiarm Strike
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 5 burst
      effects:
        - roll: Power Roll + 3
          tier1: 2 psychic damage
          tier2: 3 psychic damage; I < 2 [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 4 psychic damage; I < 3 [frightened](../../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Horrid Wail
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The first time the mournling is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 10 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).
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
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 2
keywords:
    - Undead
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/flesh-mournling
    source: mcdm.monsters.v1
might: 3
name: Flesh Mournling
organization: Horde
presence: -1
reason: 0
role: Defender
size: "2"
speed: 6
stability: 2
stamina: "35"
type: statblock
```
