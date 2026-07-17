---
agility: 1
ev: "3"
file_basename: soulwight
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
item_id: soulwight
item_name: Soulwight
keywords:
    - Undead
level: 1
might: 2
name: Soulwight
organization: Horde
presence: 1
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/soulwight
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 corruption damage
          tier2: 4 corruption damage; M < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 5 corruption damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Soulstealer Longsword
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - effect: '**Effect:** The target regains 10 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). The soulwight can''t use this maneuver again until after they strike a creature with their Soulstealer Longsword.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Stolen Vitality
      target: One ally
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time the soulwight is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).
      feature_type: trait
      icon: ⭐️
      name: Arise
      type: feature
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
keywords:
    - Undead
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/soulwight
    source: mcdm.monsters.v1
might: 2
name: Soulwight
organization: Horde
presence: 1
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "10"
type: statblock
```
