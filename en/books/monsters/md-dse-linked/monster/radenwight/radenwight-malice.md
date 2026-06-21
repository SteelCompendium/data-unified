---
features:
    - cost: 3 Malice
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Trouser Cut
      power_roll:
        formula: + 2
        tiers:
            high: 13 damage; [push](../../movement/forced-movement.md) 5, [taunted](../../condition/taunted.md) (EoT)
            low: 7 damage; [push](../../movement/forced-movement.md) 3
            mid: 10 damage; [push](../../movement/forced-movement.md) 3, [taunted](../../condition/taunted.md) (EoT)
      sections:
        - label: Effect
          text: If the target is wearing clothing covering the lower half of their body, they must use a maneuver once to pull that clothing up before they can move.
        - label: Special
          text: This ability can't be used by a [minion](../../rule/organization/minion.md).
      target: One creature
      usage: Main action
    - body: Each radenwight in the encounter [shifts](../../movement/shifting.md) up to their speed. If a radenwight ends this shift [adjacent](../../rule/combat/adjacent.md) to one or more radenwights, they can make a melee [free strike](../../feature/common/main-actions/free-strike.md) against each enemy [adjacent](../../rule/combat/adjacent.md) to them.
      cost: 5 Malice
      icon: ⭐️
      name: Rat Race
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: |-
        A radenwight uses music to coordinate living rats, forming a 10 wall of rats scurrying atop one another into unoccupied spaces anywhere on the encounter map. The wall doesn't block [line of effect](../../rule/combat/line-of-effect.md) for radenwights and their allies, but it does for other creatures as the rats coordinate their movements with the radenwights. Each square of the wall has 10 [Stamina](../../rule/health/stamina.md).

        If the last radenwight in the encounter dies and the wall is still standing, the rats let out a hideous screech as they disperse. Each enemy on the encounter map makes an Intuition test.
      name: Rally the Rodents
      power_roll:
        tiers:
            high: No effect.
            low: 7 sonic damage; the target can't take a respite activity during their next respite
            mid: 5 sonic damage
file_basename: radenwight-malice
file_dpath: monster/radenwight
flavor: At the start of any radenwight's turn, you can spend Malice to activate one of the following features.
item_id: radenwight-malice
item_name: Radenwight Malice
kind: malice
name: Radenwight Malice
scc: mcdm.monsters.v1/monster.radenwight/radenwight-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any radenwight's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 🗡 **Trouser Cut (3 [Malice](../../rule/monster/malice.md))**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](../../movement/forced-movement.md) 3
> - **12-16:** 10 damage; [push](../../movement/forced-movement.md) 3, [taunted](../../condition/taunted.md) (EoT)
> - **17+:** 13 damage; [push](../../movement/forced-movement.md) 5, [taunted](../../condition/taunted.md) (EoT)
>
> **Effect:** If the target is wearing clothing covering the lower half of their body, they must use a maneuver once to pull that clothing up before they can move.
>
> **Special:** This ability can't be used by a [minion](../../rule/organization/minion.md).

> ⭐️ **Rat Race (5 [Malice](../../rule/monster/malice.md))**
>
> Each radenwight in the encounter [shifts](../../movement/shifting.md) up to their speed. If a radenwight ends this shift [adjacent](../../rule/combat/adjacent.md) to one or more radenwights, they can make a melee [free strike](../../feature/common/main-actions/free-strike.md) against each enemy [adjacent](../../rule/combat/adjacent.md) to them.

> 🔳 **Rally the Rodents (7 [Malice](../../rule/monster/malice.md))**
>
> A radenwight uses music to coordinate living rats, forming a 10 wall of rats scurrying atop one another into unoccupied spaces anywhere on the encounter map. The wall doesn't block [line of effect](../../rule/combat/line-of-effect.md) for radenwights and their allies, but it does for other creatures as the rats coordinate their movements with the radenwights. Each square of the wall has 10 [Stamina](../../rule/health/stamina.md).
>
> If the last radenwight in the encounter dies and the wall is still standing, the rats let out a hideous screech as they disperse. Each enemy on the encounter map makes an Intuition test.
>
> - **≤11:** 7 sonic damage; the target can't take a respite activity during their next respite
> - **12-16:** 5 sonic damage
> - **17+:** No effect.
