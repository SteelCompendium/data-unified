---
agility: 3
ev: 7 for four minions
file_basename: bugbear-snare
file_dpath: monster/bugbear/statblock
free_strike: 3
intuition: 0
item_id: bugbear-snare
item_name: Bugbear Snare
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 5
might: 2
name: Bugbear Snare
organization: Minion
presence: 1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-snare
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "9"
type: statblock
with_captain: +3 bonus to speed
---

```ds-sb
agility: 3
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 6 damage
          tier3: 7 damage; A < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Cut 'Em Low!
      target: One creature or object per minion
      type: feature
      usage: Main action
free_strike: 3
intuition: 0
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-snare
    source: mcdm.monsters.v1
might: 2
name: Bugbear Snare
organization: Minion
presence: 1
reason: 0
role: Ambusher
size: 1L
speed: 6
stability: 2
stamina: "9"
type: statblock
with_captain: +3 bonus to speed
```
