---
agility: 2
ev: 3 for 4 minions
file_basename: radenwight-mischiever
file_dpath: monster/radenwight/statblock
free_strike: 2
intuition: 1
item_id: radenwight-mischiever
item_name: Radenwight Mischiever
keywords:
    - Humanoid
    - Radenwight
level: 1
might: -1
movement: Climb
name: Radenwight Mischiever
organization: Minion
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-mischiever
size: 1S
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 2
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Dagger Dance
      target: One creature per minion
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals damage to the target.
            **Effect:** The mischiever makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
        - Weapon
      name: Ready Rodent
      target: One creature
      type: feature
      usage: Triggered action
free_strike: 2
intuition: 1
keywords:
    - Humanoid
    - Radenwight
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-mischiever
    source: mcdm.monsters.v1
might: -1
movement: Climb
name: Radenwight Mischiever
organization: Minion
presence: 0
reason: 0
role: Ambusher
size: 1S
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
```
