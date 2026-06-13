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
          text: 'The high elf chooses a damage type and condition from one of the following combinations: cold damage and [slowed](scc:mcdm.heroes.v1/condition/slowed), poison damage and [weakened](scc:mcdm.heroes.v1/condition/weakened), or corruption damage and [frightened](scc:mcdm.heroes.v1/condition/frightened).'
        - label: Special
          text: This ability can't be used by a [minion](scc:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy in the area
      usage: Main action
    - body: Until the end of the round, each high elf in the encounter gains a +4 bonus to speed, and whenever a high elf uses an ability against an enemy, each high elf [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to that enemy can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      cost: 7 Malice
      icon: "\U0001F300"
      name: In Defiance of Time
flavor: At the start of any high elf's turn, you can spend Malice to activate one of the following features.
kind: malice
name: High Elf Malice
scc: mcdm.monsters.v1/monster.elves-high/high-elf-malice
type: featureblock
---

At the start of any high elf's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🌀 **Chaincast (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, whenever a high elf uses a magic ability, they can use it as if they were occupying the square of another high elf on the encounter map to whom they have line of effect.

> 🔳 **Gift From an Accursed Tome (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic**            |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 5 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Effect:** The high elf chooses a damage type and condition from one of the following combinations: cold damage and [slowed](scc:mcdm.heroes.v1/condition/slowed), poison damage and [weakened](scc:mcdm.heroes.v1/condition/weakened), or corruption damage and [frightened](scc:mcdm.heroes.v1/condition/frightened).
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; R < 1 chosen condition (save ends)
> - **12-16:** 9 damage; R < 2 chosen condition (save ends)
> - **17+:** 12 damage; R < 3 chosen condition (save ends)
>
> **Special:** This ability can't be used by a [minion](scc:mcdm.monsters.v1/rule.organization/minion).

> 🌀 **In Defiance of Time (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, each high elf in the encounter gains a +4 bonus to speed, and whenever a high elf uses an ability against an enemy, each high elf [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to that enemy can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
