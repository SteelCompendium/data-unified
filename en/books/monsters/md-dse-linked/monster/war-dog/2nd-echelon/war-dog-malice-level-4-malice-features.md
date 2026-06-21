---
features:
    - body: The war dog activates a [Malice](../../../rule/monster/malice.md) feature available to war dogs of level 3 or lower.
      cost: 3-7 Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 5 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Loyalty Unto Death
      power_roll:
        tiers:
            high: '[Push](../../../movement/forced-movement.md) 2'
            low: '[Push](../../../movement/forced-movement.md) 4; the enemy is [frightened](../../../condition/frightened.md) of the nearest non-[minion](../../../rule/organization/minion.md) war dog (save ends)'
            mid: '[Push](../../../movement/forced-movement.md) 2; the enemy is [frightened](../../../condition/frightened.md) of the nearest non-[minion](../../../rule/organization/minion.md) war dog (EoT)'
      sections:
        - label: Effect
          text: Each target who has a loyalty collar [shifts](../../../movement/shifting.md) up to their speed, then is reduced to 0 [Stamina](../../../rule/health/stamina.md). After each target's Loyalty Collar trait is resolved, each enemy [adjacent](../../../rule/combat/adjacent.md) to either target makes a Presence test.
      target: Two war dogs
      usage: Maneuver
file_basename: war-dog-malice-level-4-malice-features
file_dpath: monster/war-dog/2nd-echelon
flavor: At the start of any level 4 or higher war dog's turn, you can spend Malice to activate one of the following features.
item_id: war-dog-malice-level-4-malice-features
item_name: War Dog Malice (Level 4+ Malice Features)
kind: malice
level: 4
name: War Dog Malice (Level 4+ Malice Features)
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon/war-dog-malice-level-4-malice-features
source: mcdm.monsters.v1
type: featureblock
---

At the start of any level 4 or higher war dog's turn, you can spend [Malice](../../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Prior [Malice](../../../rule/monster/malice.md) Features (3-7 [Malice](../../../rule/monster/malice.md))**
>
> The war dog activates a [Malice](../../../rule/monster/malice.md) feature available to war dogs of level 3 or lower.

> 🏹 **Loyalty Unto Death (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** |        **Maneuver** |
> |-------------------|--------------------:|
> | **📏 Ranged 10**  | **🎯 Two war dogs** |
>
> **Effect:** Each target who has a loyalty collar [shifts](../../../movement/shifting.md) up to their speed, then is reduced to 0 [Stamina](../../../rule/health/stamina.md). After each target's Loyalty Collar trait is resolved, each enemy [adjacent](../../../rule/combat/adjacent.md) to either target makes a Presence test.
>
> - **≤11:** [Push](../../../movement/forced-movement.md) 4; the enemy is [frightened](../../../condition/frightened.md) of the nearest non-[minion](../../../rule/organization/minion.md) war dog (save ends)
> - **12-16:** [Push](../../../movement/forced-movement.md) 2; the enemy is [frightened](../../../condition/frightened.md) of the nearest non-[minion](../../../rule/organization/minion.md) war dog (EoT)
> - **17+:** [Push](../../../movement/forced-movement.md) 2
