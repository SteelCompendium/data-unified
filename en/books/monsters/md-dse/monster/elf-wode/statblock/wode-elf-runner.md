---
agility: 2
ev: 3 for four minions
file_basename: wode-elf-runner
file_dpath: monster/elf-wode/statblock
free_strike: 1
intuition: 0
item_id: wode-elf-runner
item_name: Wode Elf Runner
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
might: 0
name: Wode Elf Runner
organization: Minion
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-runner
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Spear
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Abilities targeting the runner that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-runner
    source: mcdm.monsters.v1
might: 0
name: Wode Elf Runner
organization: Minion
presence: 1
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
```
