---
features:
    - body: The war dog activates a [Malice](../../../rule/monster/malice.md) feature available to war dogs of level 9 or lower.
      cost: 3-7 Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 7 Malice
      distance: 3 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Cry Havoc
      power_roll:
        formula: + 5
        tiers:
            high: 14 psychic damage; P < 5 [frightened](../../../condition/frightened.md) (save ends)
            low: 7 psychic damage
            mid: 11 psychic damage; P < 4 [frightened](../../../condition/frightened.md) (save ends)
      sections:
        - label: Effect
          text: Each war dog within distance deals an extra 15 damage with strikes until the end of their next turn. Additionally, they end any effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md) or that ends at the end of their turn, then [shift](../../../movement/shifting.md) up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md).
        - label: Special
          text: This ability can't be used by a [minion](../../../rule/organization/minion.md).
      target: Each enemy in the area
      usage: Maneuver
file_basename: war-dog-malice-level-10-malice-features
file_dpath: monster/war-dog/4th-echelon
flavor: At the start of any level 10 or higher war dog's turn, you can spend Malice to activate one of the following features.
item_id: war-dog-malice-level-10-malice-features
item_name: War Dog Malice (Level 10+ Malice Features)
kind: malice
level: 10
name: War Dog Malice (Level 10+ Malice Features)
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon/war-dog-malice-level-10-malice-features
source: mcdm.monsters.v1
type: featureblock
---

At the start of any level 10 or higher war dog's turn, you can spend [Malice](../../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Prior [Malice](../../../rule/monster/malice.md) Features (3-7 [Malice](../../../rule/monster/malice.md))**
>
> The war dog activates a [Malice](../../../rule/monster/malice.md) feature available to war dogs of level 9 or lower.

> ❇️ **Cry Havoc (7 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic** |                  **Maneuver** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 7 psychic damage
> - **12-16:** 11 psychic damage; P < 4 [frightened](../../../condition/frightened.md) (save ends)
> - **17+:** 14 psychic damage; P < 5 [frightened](../../../condition/frightened.md) (save ends)
>
> **Effect:** Each war dog within distance deals an extra 15 damage with strikes until the end of their next turn. Additionally, they end any effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md) or that ends at the end of their turn, then [shift](../../../movement/shifting.md) up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md).
>
> **Special:** This ability can't be used by a [minion](../../../rule/organization/minion.md).
