---
agility: -3
ev: 12 for four minions
file_basename: giant-shambler-zombie
file_dpath: monster/undead/4th-echelon/statblock
free_strike: 5
immunities:
    - Corruption 10
    - poison 10
intuition: 1
item_id: giant-shambler-zombie
item_name: Giant Shambler Zombie
keywords:
    - Undead
    - Soulless
level: 10
might: 5
name: Giant Shambler Zombie
organization: Minion
presence: -2
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/giant-shambler-zombie
size: "3"
source: mcdm.monsters.v1
speed: 4
stability: 5
stamina: "17"
type: statblock
with_captain: +4 damage bonus to strikes
---

```ds-sb
agility: -3
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 5
          tier1: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier3: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Rotten Kick
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Each ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the shambler has [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 3.
      feature_type: trait
      icon: ⭐️
      name: Meat Shield
      type: feature
free_strike: 5
immunities:
    - Corruption 10
    - poison 10
intuition: 1
keywords:
    - Undead
    - Soulless
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/giant-shambler-zombie
    source: mcdm.monsters.v1
might: 5
name: Giant Shambler Zombie
organization: Minion
presence: -2
reason: -3
role: Brute
size: "3"
speed: 4
stability: 5
stamina: "17"
type: statblock
with_captain: +4 damage bonus to strikes
```
