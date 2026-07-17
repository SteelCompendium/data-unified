---
agility: 3
ev: "16"
file_basename: shadow-elf-assassin
file_dpath: monster/elf-shadow/statblock
free_strike: 7
intuition: 1
item_id: shadow-elf-assassin
item_name: Shadow Elf Assassin
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 6
might: 0
movement: Climb
name: Shadow Elf Assassin
organization: Platoon
presence: 1
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-assassin
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "70"
type: statblock
---

```ds-sb
agility: 3
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage
          tier2: 15 damage
          tier3: 18 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Lumina Assault
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 4 x 1 line within 10
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage; I < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 10 damage; I < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 12 damage; I < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Splitbow
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The assassin ignores concealment created by darkness. While the assassin is in direct sunlight, they have damage weakness 3. While the assassin has concealment, they have damage immunity 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 7
intuition: 1
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-assassin
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Shadow Elf Assassin
organization: Platoon
presence: 1
reason: 2
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "70"
type: statblock
```
