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
            high: 9 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            low: 4 corruption damage; A < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
            mid: 6 corruption damage; A < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      sections:
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy and object in the area
      usage: Maneuver
    - body: Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.
      cost: 5 Malice
      icon: ⭐️
      name: Exploit Opening
    - body: Each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) human in the encounter regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 times their level.
      cost: 7 Malice
      icon: ⭐️
      name: Staying Power
flavor: At the start of any human's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Human Malice
scc: mcdm.monsters.v1/monster.human/human-malice
type: featureblock
---

At the start of any human's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🔳 **Alchemical Device (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic, Ranged** |                             **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------------|-----------------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 corruption damage; A < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 6 corruption damage; A < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 9 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Special:** This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).

> ⭐️ **Exploit Opening (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.

> ⭐️ **Staying Power (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) human in the encounter regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 times their level.
