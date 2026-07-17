---
agility: 3
ev: '-'
file_basename: shadow-elf-shade
file_dpath: monster/retainer/statblock
free_strike: 5
intuition: 2
item_id: shadow-elf-shade
item_name: Shadow Elf Shade
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
might: 1
movement: Climb
name: Shadow Elf Shade
organization: Retainer
presence: 1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.retainer.statblock/shadow-elf-shade
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "48"
type: statblock
---

```ds-sb
agility: 3
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 3
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 6 damage
          tier2: 10 damage
          tier3: 13 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Gloom Dagger
      target: One creature or object
      type: feature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      effects:
        - effect: '**Effect:** Until the end of the next turn, the area is filled with darkness. The shade''s mentor ignores concealment created by this darkness.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Duskfall
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: The shade ignores concealment created by darkness. While the shade is in direct sunlight, they have [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 3. While the shade has concealment, they have [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 5
intuition: 2
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/shadow-elf-shade
    source: mcdm.monsters.v1
might: 1
movement: Climb
name: Shadow Elf Shade
organization: Retainer
presence: 1
reason: 0
role: Ambusher
size: 1M
speed: 5
stability: 0
stamina: "48"
type: statblock
```
