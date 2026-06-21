---
features:
    - body: The war dog activates a [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) feature available to war dogs of level 9 or lower.
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
            high: 14 psychic damage; P < 5 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
            low: 7 psychic damage
            mid: 11 psychic damage; P < 4 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      sections:
        - label: Effect
          text: Each war dog within distance deals an extra 15 damage with strikes until the end of their next turn. Additionally, they end any effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their turn, then [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy in the area
      usage: Maneuver
flavor: At the start of any level 10 or higher war dog's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 10
name: War Dog Malice (Level 10+ Malice Features)
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon/war-dog-malice-level-10-malice-features
type: featureblock
---

At the start of any level 10 or higher war dog's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Prior [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) Features (3-7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The war dog activates a [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) feature available to war dogs of level 9 or lower.

> ❇️ **Cry Havoc (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |                  **Maneuver** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 7 psychic damage
> - **12-16:** 11 psychic damage; P < 4 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 14 psychic damage; P < 5 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** Each war dog within distance deals an extra 15 damage with strikes until the end of their next turn. Additionally, they end any effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their turn, then [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
>
> **Special:** This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
