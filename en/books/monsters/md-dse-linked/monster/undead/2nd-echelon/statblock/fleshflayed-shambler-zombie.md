---
agility: -1
ev: 6 for four minions
file_basename: fleshflayed-shambler-zombie
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 0
item_id: fleshflayed-shambler-zombie
item_name: Fleshflayed Shambler Zombie
keywords:
    - Undead
    - Soulless
level: 4
might: 3
name: Fleshflayed Shambler Zombie
organization: Minion
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/fleshflayed-shambler-zombie
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "9"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: -1
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Bone Carvers
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any [adjacent](../../../../rule/combat/adjacent.md) enemy who [grabs](../../../../condition/grabbed.md) the fleshflayed shambler or uses melee ability against them takes 2 damage.
      feature_type: trait
      icon: ⭐️
      name: Fleshfused Spines
      type: feature
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 0
keywords:
    - Undead
    - Soulless
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/fleshflayed-shambler-zombie
    source: mcdm.monsters.v1
might: 3
name: Fleshflayed Shambler Zombie
organization: Minion
presence: 0
reason: 0
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "9"
type: statblock
with_captain: +2 damage bonus to strikes
```
