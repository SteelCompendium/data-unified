---
features:
    - body: One war dog acting this turn tears apart a nearby corpse of a humanoid and incorporates its body parts into their own. The war dog regains [Stamina](../../../rule/health/stamina.md) equal to 5 times their level.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Reconstitute
    - cost: 5 Malice
      distance: 4 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Fire for Effect
      power_roll:
        tiers:
            high: 5 fire damage
            low: 5 fire damage; [slowed](../../../condition/slowed.md) or [weakened](../../../condition/weakened.md) (save ends)
            mid: 5 fire damage; [slowed](../../../condition/slowed.md) or [weakened](../../../condition/weakened.md) (EoT)
      sections:
        - label: Effect
          text: Each target makes an **Agility test**. The same condition is imposed on each affected target.
      target: Each creature in the area
      usage: Maneuver
    - body: Each war dog [minion](../../../rule/organization/minion.md) in the encounter [shifts](../../../movement/shifting.md) up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). A [minion](../../../rule/organization/minion.md) who does so is then reduced to 0 [Stamina](../../../rule/health/stamina.md).
      cost: 7 Malice
      icon: ⭐️
      name: Fodder Run
flavor: At the start of any war dog's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 1
name: War Dog Malice (Level 1+ Malice Features)
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon/war-dog-malice-level-1-malice-features
type: featureblock
---

At the start of any war dog's turn, you can spend [Malice](../../../rule/monster/malice.md) to activate one of the following features.

> 👤 **Reconstitute (3 Malice)**
>
> One war dog acting this turn tears apart a nearby corpse of a humanoid and incorporates its body parts into their own. The war dog regains [Stamina](../../../rule/health/stamina.md) equal to 5 times their level.

> 🔳 **Fire for Effect (5 Malice)**
>
> | **Area, Magic, Ranged**     |               **Maneuver** |
> |-----------------------------|------------------------------:|
> | **📏 4 cube within 10**     | **🎯 Each creature in the area** |
>
> **Effect:** Each target makes an **Agility test**. The same condition is imposed on each affected target.
>
> - **≤11:** 5 fire damage; [slowed](../../../condition/slowed.md) or [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 5 fire damage; [slowed](../../../condition/slowed.md) or [weakened](../../../condition/weakened.md) (EoT)
> - **17+:** 5 fire damage

> ⭐️ **Fodder Run (7 Malice)**
>
> Each war dog [minion](../../../rule/organization/minion.md) in the encounter [shifts](../../../movement/shifting.md) up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). A [minion](../../../rule/organization/minion.md) who does so is then reduced to 0 [Stamina](../../../rule/health/stamina.md).
