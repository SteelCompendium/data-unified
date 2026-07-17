---
agility: 2
ev: 10 for four minions
file_basename: minotaur-bully
file_dpath: monster/minotaur/statblock
free_strike: 4
intuition: 3
item_id: minotaur-bully
item_name: Minotaur Bully
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 8
might: 4
name: Minotaur Bully
organization: Minion
presence: -1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-bully
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "14"
type: statblock
with_captain: +3 damage bonus to strikes
---

```ds-sb
agility: 2
ev: 10 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2 or ranged 5
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 7 damage
          tier3: 9 damage; I < 4 [taunted](../../../condition/taunted.md) (EoT) or [frightened](../../../condition/frightened.md) of all minotaurs (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Javelin and Bellow
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The bully can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
      feature_type: trait
      icon: ⭐️
      name: Minotaur Sense
      type: feature
free_strike: 4
intuition: 3
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-bully
    source: mcdm.monsters.v1
might: 4
name: Minotaur Bully
organization: Minion
presence: -1
reason: 0
role: Brute
size: "2"
speed: 6
stability: 2
stamina: "14"
type: statblock
with_captain: +3 damage bonus to strikes
```
