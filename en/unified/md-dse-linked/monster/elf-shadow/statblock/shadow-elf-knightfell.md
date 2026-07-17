---
agility: 2
ev: "12"
file_basename: shadow-elf-knightfell
file_dpath: monster/elf-shadow/statblock
free_strike: 5
intuition: 3
item_id: shadow-elf-knightfell
item_name: Shadow Elf Knightfell
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
might: 0
movement: Climb
name: Shadow Elf Knightfell
organization: Platoon
presence: 2
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-knightfell
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
      distance: Ranged 3
      effects:
        - roll: Power Roll + 3
          tier1: 8 corruption damage
          tier2: 12 corruption damage; R < 2 [taunted](../../../condition/taunted.md) (EoT)
          tier3: 15 corruption damage; R < 3 [taunted](../../../condition/taunted.md) (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Suffusing Strike
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 2
      effects:
        - effect: |-
            **Trigger:** An enemy within distance makes a strike against the target.
            **Effect:** The target takes half the damage and the knightfell takes the other half.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Melee
      name: Trick of the Eye
      target: One ally
      type: feature
      usage: Triggered action
    - effects:
        - effect: The knightfell ignores concealment created by darkness. While the knightfell is in direct sunlight, they have damage weakness 3. While the knightfell has concealment, they have damage immunity 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 5
intuition: 3
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-knightfell
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Shadow Elf Knightfell
organization: Platoon
presence: 2
reason: 0
role: Defender
size: 1M
speed: 5
stability: 0
stamina: "70"
type: statblock
```
