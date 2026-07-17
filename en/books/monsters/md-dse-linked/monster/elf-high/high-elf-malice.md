---
features:
    - body: Until the end of the round, whenever a high elf uses a magic ability, they can use it as if they were occupying the square of another high elf on the encounter map to whom they have line of effect.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Chaincast
    - cost: 5 Malice
      distance: 5 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Gift From an Accursed Tome
      power_roll:
        formula: + 2
        tiers:
            high: 12 damage; R < 3 chosen condition (save ends)
            low: 5 damage; R < 1 chosen condition (save ends)
            mid: 9 damage; R < 2 chosen condition (save ends)
      sections:
        - label: Effect
          text: 'The high elf chooses a damage type and condition from one of the following combinations: cold damage and [slowed](../../condition/slowed.md), poison damage and [weakened](../../condition/weakened.md), or corruption damage and [frightened](../../condition/frightened.md).'
        - label: Special
          text: This ability can't be used by a [minion](../../rule/organization/minion.md).
      target: Each enemy in the area
      usage: Main action
    - body: Until the end of the round, each high elf in the encounter gains a +4 bonus to speed, and whenever a high elf uses an ability against an enemy, each high elf [adjacent](../../rule/combat/adjacent.md) to that enemy can make a [free strike](../../feature/common/main-actions/free-strike.md) against them.
      cost: 7 Malice
      icon: "\U0001F300"
      name: In Defiance of Time
file_basename: high-elf-malice
file_dpath: monster/elf-high
flavor: At the start of any high elf's turn, you can spend Malice to activate one of the following features.
item_id: high-elf-malice
item_name: High Elf Malice
kind: malice
name: High Elf Malice
scc: mcdm.monsters.v1/monster.elf-high/high-elf-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Until the end of the round, whenever a high elf uses a magic ability, they can use it as if they were occupying the square of another high elf on the encounter map to whom they have line of effect.
      cost: 3 Malice
      icon: "\U0001F300"
      name: Chaincast
    - cost: 5 Malice
      distance: 5 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Gift From an Accursed Tome
      power_roll:
        formula: + 2
        tiers:
            high: 12 damage; R < 3 chosen condition (save ends)
            low: 5 damage; R < 1 chosen condition (save ends)
            mid: 9 damage; R < 2 chosen condition (save ends)
      sections:
        - label: Effect
          text: 'The high elf chooses a damage type and condition from one of the following combinations: cold damage and [slowed](../../condition/slowed.md), poison damage and [weakened](../../condition/weakened.md), or corruption damage and [frightened](../../condition/frightened.md).'
        - label: Special
          text: This ability can't be used by a [minion](../../rule/organization/minion.md).
      target: Each enemy in the area
      usage: Main action
    - body: Until the end of the round, each high elf in the encounter gains a +4 bonus to speed, and whenever a high elf uses an ability against an enemy, each high elf [adjacent](../../rule/combat/adjacent.md) to that enemy can make a [free strike](../../feature/common/main-actions/free-strike.md) against them.
      cost: 7 Malice
      icon: "\U0001F300"
      name: In Defiance of Time
flavor: At the start of any high elf's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.elf-high/high-elf-malice
    source: mcdm.monsters.v1
name: High Elf Malice
type: featureblock
```
