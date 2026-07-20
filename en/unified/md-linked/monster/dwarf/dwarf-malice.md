---
features:
    - body: A dwarf can destroy one [adjacent](../../rule/combat/adjacent.md) object or square of wall for each 3 [Malice](../../rule/monster/malice.md) spent. Each enemy [adjacent](../../rule/combat/adjacent.md) to the destroyed object or square takes the object's Stamina in damage (3 for wood, 6 for stone, or 9 for metal).
      cost: 3 Malice
      icon: "\U0001F464"
      name: Breaching Charge
    - body: Each dwarf acting this turn can automatically climb at full speed while moving. At any point during this movement, they can make a [free strike](../../feature/common/main-actions/free-strike.md).
      cost: 5 Malice
      icon: ⭐️
      name: Rappelling Barrage
    - cost: 7 Malice
      distance: 10 x 1 line within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Snaring Line
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](../../condition/restrained.md) (EoT)
            mid: 6 damage; [slowed](../../condition/slowed.md) (EoT)
      sections:
        - label: Effect
          text: Each target makes an **Agility test**.
        - label: Special
          text: This ability can't be used by a [minion](../../rule/organization/minion.md).
      target: Each enemy in the area
      trailing: The snaring line remains until the end of the encounter. Any enemy who moves into the area for the first time in a round or starts their turn there must make the test.
      usage: Main action
flavor: At the start of any dwarf's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Dwarf Malice
scc: mcdm.monsters.v1/monster.dwarf/dwarf-malice
type: featureblock
---

At the start of any dwarf's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 👤 **Breaching Charge (3 [Malice](../../rule/monster/malice.md))**
>
> A dwarf can destroy one [adjacent](../../rule/combat/adjacent.md) object or square of wall for each 3 [Malice](../../rule/monster/malice.md) spent. Each enemy [adjacent](../../rule/combat/adjacent.md) to the destroyed object or square takes the object's Stamina in damage (3 for wood, 6 for stone, or 9 for metal).

> ⭐️ **Rappelling Barrage (5 [Malice](../../rule/monster/malice.md))**
>
> Each dwarf acting this turn can automatically climb at full speed while moving. At any point during this movement, they can make a [free strike](../../feature/common/main-actions/free-strike.md).

> 🔳 **Snaring Line (7 [Malice](../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged**      |               **[Main action](../../rule/combat/turn.md)** |
> |------------------------------|------------------------------:|              
> | **📏 10 x 1 line within 10** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes an **Agility test**.
>
> - **≤11:** 8 damage; [restrained](../../condition/restrained.md) (EoT)
> - **12-16:** 6 damage; [slowed](../../condition/slowed.md) (EoT)
> - **17+:** No effect.
>
> The snaring line remains until the end of the encounter. Any enemy who moves into the area for the first time in a round or starts their turn there must make the test.
>
> **Special:** This ability can't be used by a [minion](../../rule/organization/minion.md).
