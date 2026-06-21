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
      name: Go for the Jugular
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: If the target is [grabbed](../../../condition/grabbed.md) or the retainer had an edge on the power roll, the retainer gains 2 [surges](../../../rule/resource/surge.md).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 1 or ranged 5
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Hamstring Slice
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 15 damage; M < STRONG [slowed](../../../condition/slowed.md) and the target can't used triggered actions ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 damage; M < WEAK [slowed](../../../condition/slowed.md) (EoT)
            mid: 10 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: The retainer and their mentor can each move up to their speed.
      target: One creature
      usage: Main Action
    - cost: Encounter
      distance: Melee 1 or ranged 5
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Hold 'Em Down
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; a size 1 or smaller target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
            low: 11 damage; a size 1 or smaller target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
            mid: 16 damage; a size 1 or smaller target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The retainer gains 2 [surges](../../../rule/resource/surge.md) when any creature makes a strike against a target [grabbed](../../../condition/grabbed.md) this way.
      target: One creature
      usage: Main Action
file_basename: ambusher
file_dpath: monster/retainer/role-advancement
item_id: ambusher
item_name: Ambusher Abilities
name: Ambusher Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/ambusher
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 🗡 **Go for the Jugular (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 9 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 12 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** If the target is [grabbed](../../../condition/grabbed.md) or the retainer had an edge on the power roll, the retainer gains 2 [surges](../../../rule/resource/surge.md).

> **Level 7 Role Advancement Ability**

> ⚔️ **Hamstring Slice (Encounter)**
>
> | **Melee, Ranged, Strike, Weapon** |     **Main Action** |
> |-----------------------------------|--------------------:|
> | **📏 Melee 1 or ranged 5**        | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; M < WEAK [slowed](../../../condition/slowed.md) (EoT)
> - **12-16:** 10 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 15 damage; M < STRONG [slowed](../../../condition/slowed.md) and the target can't used triggered actions ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** The retainer and their mentor can each move up to their speed.

> **Level 10 Role Advancement Ability**

> ⚔️ **Hold 'Em Down (Encounter)**
>
> | **Melee, Ranged, Strike, Weapon** |     **Main Action** |
> |-----------------------------------|--------------------:|
> | **📏 Melee 1 or ranged 5**        | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 11 damage; a size 1 or smaller target who has M < WEAK is [grabbed](../../../condition/grabbed.md)
> - **12-16:** 16 damage; a size 1 or smaller target who has M < AVERAGE is [grabbed](../../../condition/grabbed.md)
> - **17+:** 21 damage; a size 1 or smaller target who has M < STRONG is [grabbed](../../../condition/grabbed.md)
>
> **Effect:** The retainer gains 2 [surges](../../../rule/resource/surge.md) when any creature makes a strike against a target [grabbed](../../../condition/grabbed.md) this way.
