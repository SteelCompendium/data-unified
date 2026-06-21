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
      name: Unholy Attraction
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage, pull 4
            low: 8 damage; pull 1
            mid: 12 damage; pull 2
      sections:
        - label: Effect
          text: A target who is pulled [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the flameslinger and who has P < AVERAGE is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 3 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 10
      name: Fire Spiral
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
            low: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
            mid: 12 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      sections:
        - label: Effect
          text: If the flameslinger's mentor is within 10 squares of the flameslinger, the mentor can be the source of the burst instead of the flameslinger.
      target: Each enemy in the area
      usage: Main action
file_basename: hobgoblin-flameslinger
file_dpath: monster/retainer/advancement-features
item_id: hobgoblin-flameslinger
item_name: Hobgoblin Flameslinger Advancement Features
name: Hobgoblin Flameslinger Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/hobgoblin-flameslinger
source: mcdm.monsters.v1
type: featureblock
---

> **Level 7 Retainer Advancement Ability**

> 🔳 **Unholy Attraction (Encounter)**
>
> | **Area, Magic, Ranged** |               **Main action** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; pull 1
> - **12-16:** 12 damage; pull 2
> - **17+:** 16 damage, pull 4
>
> **Effect:** A target who is pulled [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the flameslinger and who has P < AVERAGE is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).

> **Level 10 Retainer Advancement Ability**

> ❇️ **Fire Spiral (Encounter)**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 12 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
>
> **Effect:** If the flameslinger's mentor is within 10 squares of the flameslinger, the mentor can be the source of the burst instead of the flameslinger.
