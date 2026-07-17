---
agility: 3
ev: 6 for four minions
file_basename: shadow-elf-dusk-mage
file_dpath: monster/elf-shadow/statblock
free_strike: 2
intuition: 0
item_id: shadow-elf-dusk-mage
item_name: Shadow Elf Dusk Mage
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
might: 0
movement: Climb
name: Shadow Elf Dusk Mage
organization: Minion
presence: 0
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-dusk-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 2 damage
          tier2: 4 damage; A < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 6 damage; A < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Gloom Bolt
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The dusk mage ignores concealment created by darkness. While the dusk mage is in direct sunlight, they have damage weakness 3. While the dusk mage has concealment, they have damage immunity 3.
      feature_type: trait
      icon: ⭐️
      name: Of the Umbra
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Shadow Elf
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.elf-shadow.statblock/shadow-elf-dusk-mage
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Shadow Elf Dusk Mage
organization: Minion
presence: 0
reason: 2
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: Gain an edge on strikes
```
