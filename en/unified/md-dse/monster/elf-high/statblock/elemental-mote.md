---
agility: 0
ev: 3 for four minions
file_basename: elemental-mote
file_dpath: monster/elf-high/statblock
free_strike: 1
intuition: 0
item_id: elemental-mote
item_name: Elemental Mote
keywords:
    - Elemental
    - High Elf
    - Soulless
level: 1
might: 0
movement: Fly
name: Elemental Mote
organization: Minion
presence: 2
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.elf-high.statblock/elemental-mote
size: 1T
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 0
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage; R < 1 damage weakness 3 (save ends)
          tier3: 3 damage; R < 2 damage weakness 3 (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Dweomer Plume
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: On their turn, the mote can leave the encounter in a flash of light to revive one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) dead soot crow, brambleguard, or ceramic horse. The revived creature returns with 3 Stamina.
      feature_type: trait
      icon: ⭐️
      name: Spark of Life
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Elemental
    - High Elf
    - Soulless
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/elemental-mote
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: Elemental Mote
organization: Minion
presence: 2
reason: 0
role: Hexer
size: 1T
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +2 bonus to speed
```
