---
agility: 2
ev: "6"
file_basename: high-elf-bloodletter
file_dpath: monster/elf-high/statblock
free_strike: 4
intuition: 1
item_id: high-elf-bloodletter
item_name: High Elf Bloodletter
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Bloodletter
organization: Platoon
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-bloodletter
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage
          tier3: 12 damage; R < 2 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Razor's Edge
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 1 burst
      effects:
        - effect: '**Effect:** Until the end of the next round, a cloud of blood vapor fills the area. The cloud blocks line of effect for enemies, and any enemy has damage weakness 3 while in the area. The bloodletter can then [shift](../../../movement/shifting.md) up to their speed, and can attempt to hide if they end that shift with concealment.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Blood Haze
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the start of each of their turns, the bloodletter can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-bloodletter
    source: mcdm.monsters.v1
might: 0
name: High Elf Bloodletter
organization: Platoon
presence: 0
reason: 0
role: Ambusher
size: 1M
speed: 7
stability: 0
stamina: "30"
type: statblock
```
