---
features:
    - cost: 3 Malice
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Alchemical Device
      power_roll:
        formula: + 2
        tiers:
            high: 9 corruption damage; A < 2 [restrained](../../condition/restrained.md) (save ends)
            low: 4 corruption damage; A < 0 [slowed](../../condition/slowed.md) (save ends)
            mid: 6 corruption damage; A < 1 [slowed](../../condition/slowed.md) (save ends)
      sections:
        - label: Special
          text: This ability can't be used by a [minion](../../rule/organization/minion.md).
      target: Each enemy and object in the area
      usage: Maneuver
    - body: Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.
      cost: 5 Malice
      icon: ⭐️
      name: Exploit Opening
    - body: Each non-[minion](../../rule/organization/minion.md) human in the encounter regains [Stamina](../../rule/health/stamina.md) equal to 5 times their level.
      cost: 7 Malice
      icon: ⭐️
      name: Staying Power
flavor: At the start of any human's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Human Malice
scc: mcdm.monsters.v1/monster.human/human-malice
type: featureblock
---

At the start of any human's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 🔳 **Alchemical Device (3 [Malice](../../rule/monster/malice.md))**
>
> | **Area, Magic, Ranged** |                             **Maneuver** |
> |-------------------------|-----------------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 corruption damage; A < 0 [slowed](../../condition/slowed.md) (save ends)
> - **12-16:** 6 corruption damage; A < 1 [slowed](../../condition/slowed.md) (save ends)
> - **17+:** 9 corruption damage; A < 2 [restrained](../../condition/restrained.md) (save ends)
>
> **Special:** This ability can't be used by a [minion](../../rule/organization/minion.md).

> ⭐️ **Exploit Opening (5 [Malice](../../rule/monster/malice.md))**
>
> Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.

> ⭐️ **Staying Power (7 [Malice](../../rule/monster/malice.md))**
>
> Each non-[minion](../../rule/organization/minion.md) human in the encounter regains [Stamina](../../rule/health/stamina.md) equal to 5 times their level.
