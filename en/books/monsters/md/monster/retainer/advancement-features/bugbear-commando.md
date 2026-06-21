---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Face Grab
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 13 damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            low: 6 damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            mid: 9 damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      sections:
        - label: Effect
          text: While the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, they can't communicate and all creatures and objects have concealment from them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 7
      name: Shadow Drag
      power_roll:
        formula: + highest characteristic
        tiers:
            high: Pull 12
            low: Pull 8
            mid: Pull 10
      sections:
        - label: Effect
          text: The target takes 1 damage for each square they are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement).
      target: One creature or object
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 10
      name: Neck Snap
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      sections:
        - label: Effect
          text: The target takes 15 damage, they are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), and they fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).
      target: One creature grabbed by the commando
      usage: Main action
name: Bugbear Commando Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/bugbear-commando
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🗡 **Face Grab (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 9 damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 13 damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** While the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, they can't communicate and all creatures and objects have concealment from them.

> **Level 7 Retainer Advancement Ability**

> 🏹 **Shadow Drag (Encounter)**
>
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** Pull 8
> - **12-16:** Pull 10
> - **17+:** Pull 12
>
> **Effect:** The target takes 1 damage for each square they are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement).

> **Level 10 Retainer Advancement Ability**

> 🗡 **Neck Snap (Encounter)**
>
> | **Melee**      |                             **Main action** |
> |----------------|--------------------------------------------:|
> | **📏 Melee 1** | **🎯 One creature grabbed by the commando** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 12 damage
> - **12-16:** 18 damage
> - **17+:** 24 damage
>
> **Effect:** The target takes 15 damage, they are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), and they fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).
