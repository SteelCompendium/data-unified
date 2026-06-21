---
features:
    - cost: Encounter
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      level: 7
      name: Flames of Revenge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage
            low: 6 corruption damage
            mid: 10 corruption damage
      sections:
        - label: Effect
          text: If the defector's mentor is in the area, the mentor burns with flame until the end of the defector's next turn. While this fire burns the mentor has fire immunity 10, and any creature who targets the mentor with a strike takes 10 fire damage.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 5 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      level: 10
      name: Hell On Earth
      sections:
        - label: Effect
          text: The area burns with infernal fire until the end of the devil's next turn. Any enemy of the defector who ends their turn in the area takes 10 fire damage, and if they have P < AVERAGE they are [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends).
      target: Special
      usage: Main action
file_basename: devil-defector
file_dpath: monster/retainer/advancement-features
item_id: devil-defector
item_name: Devil Defector Advancement Features
name: Devil Defector Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/devil-defector
source: mcdm.monsters.v1
type: featureblock
---

> **Level 7 Retainer Advancement Ability**

> 🔳 **Flames of Revenge (Encounter)**
>
> | **Area, Magic, Ranged** |               **Main action** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 corruption damage
> - **12-16:** 10 corruption damage
> - **17+:** 14 corruption damage
>
> **Effect:** If the defector's mentor is in the area, the mentor burns with flame until the end of the defector's next turn. While this fire burns the mentor has fire immunity 10, and any creature who targets the mentor with a strike takes 10 fire damage.

> **Level 10 Retainer Advancement Ability**

> 🔳 **Hell On Earth (Encounter)**
>
> | **Area, Magic, Ranged** | **Main action** |
> |-------------------------|----------------:|
> | **📏 5 cube within 10** |  **🎯 Special** |
>
> **Effect:** The area burns with infernal fire until the end of the devil's next turn. Any enemy of the defector who ends their turn in the area takes 10 fire damage, and if they have P < AVERAGE they are [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends).
