---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Cavalry Charge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 damage
            low: 6 damage
            mid: 8 damage
      sections:
        - label: Effect
          text: If this ability is used as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, the mount's rider can use a free triggered action to make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the same target.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Range 5
      icon: "\U0001F464"
      keywords:
        - '-'
      level: 7
      name: Giddyup!
      sections:
        - label: Effect
          text: The mount [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) twice their speed. They can jump as part of this movement.
      target: Self
      usage: Move action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Rearing Trample
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 10 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 15 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      sections:
        - label: Effect
          text: A target knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) this way or who is already [prone](scc.v1:mcdm.heroes.v1/condition/prone) takes an extra 5 damage.
      target: Each enemy in the area
      usage: Main action
name: Mount Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/mount
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🗡 **Cavalry Charge (Encounter)**
>
> | **Charge, Melee, Strike, Weapon** |  **Main action** |
> |-----------------------------------|-----------------:|
> | **📏 Melee 1**                    | **🎯 One enemy** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage
> - **12-16:** 8 damage
> - **17+:** 11 damage
>
> **Effect:** If this ability is used as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, the mount's rider can use a free triggered action to make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the same target.

> **Level 7 Role Advancement Ability**

> 👤 **Giddyup! (Encounter)**
>
> | **-**          | **Move action** |
> |----------------|----------------:|
> | **📏 Range 5** |     **🎯 Self** |
>
> **Effect:** The mount [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) twice their speed. They can jump as part of this movement.

> **Level 10 Role Advancement Ability**

> ❇️ **Rearing Trample (Encounter)**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 10 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 15 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 21 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **Effect:** A target knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) this way or who is already [prone](scc.v1:mcdm.heroes.v1/condition/prone) takes an extra 5 damage.
