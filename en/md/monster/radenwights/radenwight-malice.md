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
            high: 13 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5, [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT)
            low: 7 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
            mid: 10 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3, [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT)
      sections:
        - label: Effect
          text: If the target is wearing clothing covering the lower half of their body, they must use a maneuver once to pull that clothing up before they can move.
        - label: Special
          text: This ability can't be used by a [minion](scc:mcdm.monsters.v1/rule.organization/minion).
      target: One creature
      usage: Main action
    - body: Each radenwight in the encounter [shifts](scc:mcdm.heroes.v1/movement/shifting) up to their speed. If a radenwight ends this shift [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to one or more radenwights, they can make a melee [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each enemy [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to them.
      cost: 5 Malice
      icon: ⭐️
      name: Rat Race
    - body: |-
        A radenwight uses music to coordinate living rats, forming a 10 wall of rats scurrying atop one another into unoccupied spaces anywhere on the encounter map. The wall doesn't block [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect) for radenwights and their allies, but it does for other creatures as the rats coordinate their movements with the radenwights. Each square of the wall has 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).

        If the last radenwight in the encounter dies and the wall is still standing, the rats let out a hideous screech as they disperse. Each enemy on the encounter map makes an Intuition test.
      cost: 7 Malice
      icon: "\U0001F533"
      name: Rally the Rodents
      power_roll:
        tiers:
            high: No effect.
            low: 7 sonic damage; the target can't take a respite activity during their next respite
            mid: 5 sonic damage
flavor: At the start of any radenwight's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Radenwight Malice
scc: mcdm.monsters.v1/monster.radenwights/radenwight-malice
type: featureblock
---

At the start of any radenwight's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🗡 **Trouser Cut (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
> - **12-16:** 10 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3, [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT)
> - **17+:** 13 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5, [taunted](scc:mcdm.heroes.v1/condition/taunted) (EoT)
>
> **Effect:** If the target is wearing clothing covering the lower half of their body, they must use a maneuver once to pull that clothing up before they can move.
>
> **Special:** This ability can't be used by a [minion](scc:mcdm.monsters.v1/rule.organization/minion).

> ⭐️ **Rat Race (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Each radenwight in the encounter [shifts](scc:mcdm.heroes.v1/movement/shifting) up to their speed. If a radenwight ends this shift [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to one or more radenwights, they can make a melee [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each enemy [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to them.

> 🔳 **Rally the Rodents (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> A radenwight uses music to coordinate living rats, forming a 10 wall of rats scurrying atop one another into unoccupied spaces anywhere on the encounter map. The wall doesn't block [line of effect](scc:mcdm.heroes.v1/rule.combat/line-of-effect) for radenwights and their allies, but it does for other creatures as the rats coordinate their movements with the radenwights. Each square of the wall has 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
>
> If the last radenwight in the encounter dies and the wall is still standing, the rats let out a hideous screech as they disperse. Each enemy on the encounter map makes an Intuition test.
>
> - **≤11:** 7 sonic damage; the target can't take a respite activity during their next respite
> - **12-16:** 5 sonic damage
> - **17+:** No effect.
