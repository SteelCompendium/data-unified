---
agility: 3
ev: 6 for four minions
file_basename: shadow-elf-sniper
file_dpath: monster/elf-shadow/statblock
free_strike: 3
intuition: 0
item_id: shadow-elf-sniper
item_name: Shadow Elf Sniper
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
might: 1
movement: Climb
name: Shadow Elf Sniper
organization: Minion
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-sniper
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 7
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Lumina Arrow
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The sniper ignores concealment created by darkness. While the sniper is in direct sunlight, they have damage weakness 3. While the sniper has concealment, they have damage immunity 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-sniper
    source: mcdm.monsters.v1
might: 1
movement: Climb
name: Shadow Elf Sniper
organization: Minion
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: +2 damage bonus to strikes
```
