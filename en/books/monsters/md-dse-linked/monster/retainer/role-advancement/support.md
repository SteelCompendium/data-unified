---
features:
    - distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 4
      name: Battlefield Medic
      sections:
        - label: Effect
          text: The target spends a [Recovery](../../../rule/health/recoveries.md), and ability rolls against the target take a bane until the start of the retainer's next turn.
      target: Self or one ally
      usage: Maneuver
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Focus Fire
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 18 damage
            low: 9 damage
            mid: 13 damage
      sections:
        - label: Effect
          text: One ally within distance gains 2 [surges](../../../rule/resource/surge.md).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 10
      name: Back from the Dead
      sections:
        - label: Effect
          text: If the target is at or below 0 [Stamina](../../../rule/health/stamina.md), or if they have died due to [Stamina](../../../rule/health/stamina.md) loss since the end of the retainer's last turn, the target is alive with 1 [Stamina](../../../rule/health/stamina.md) and can spend a [Recovery](../../../rule/health/recoveries.md).
      target: One ally
      usage: Main action
file_basename: support
file_dpath: monster/retainer/role-advancement
item_id: support
item_name: Support Abilities
name: Support Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/support
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🗡 **Battlefield Medic**
>
> | **Melee**      |            **Maneuver** |
> |----------------|------------------------:|
> | **📏 Melee 1** | **🎯 Self or one ally** |
>
> **Effect:** The target spends a [Recovery](../../../rule/health/recoveries.md), and ability rolls against the target take a bane until the start of the retainer's next turn.

> **Level 7 Role Advancement Ability**

> 🏹 **Focus Fire (Encounter)**
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> |----------------------------|--------------------:|
> | **📏 Ranged 5**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 9 damage
> - **12-16:** 13 damage
> - **17+:** 18 damage
>
> **Effect:** One ally within distance gains 2 [surges](../../../rule/resource/surge.md).

> **Level 10 Role Advancement Ability**

> 🗡 **Back from the Dead (Encounter)**
>
> | **Melee**      | **Main action** |
> |----------------|----------------:|
> | **📏 Melee 1** | **🎯 One ally** |
>
> **Effect:** If the target is at or below 0 [Stamina](../../../rule/health/stamina.md), or if they have died due to [Stamina](../../../rule/health/stamina.md) loss since the end of the retainer's last turn, the target is alive with 1 [Stamina](../../../rule/health/stamina.md) and can spend a [Recovery](../../../rule/health/recoveries.md).
