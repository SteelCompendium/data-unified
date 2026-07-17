---
agility: 2
ev: "12"
file_basename: shadow-elf-panther
file_dpath: monster/elf-shadow/statblock
free_strike: 6
intuition: 1
item_id: shadow-elf-panther
item_name: Shadow Elf Panther
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
might: 3
movement: Climb
name: Shadow Elf Panther
organization: Platoon
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-panther
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "70"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 13 damage
          tier3: 16 damage; I < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Dusk Cleave
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 2 burst
      effects:
        - roll: Power Roll + 3
          tier1: 5 corruption damage
          tier2: 8 corruption damage; I < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 10 corruption damage; I < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Bladestorm
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The panther ignores concealment created by darkness. While the panther is in direct sunlight, they have damage weakness 3. While the panther has concealment, they have damage immunity 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 6
intuition: 1
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-panther
    source: mcdm.monsters.v1
might: 3
movement: Climb
name: Shadow Elf Panther
organization: Platoon
presence: 1
reason: -1
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "70"
type: statblock
```
