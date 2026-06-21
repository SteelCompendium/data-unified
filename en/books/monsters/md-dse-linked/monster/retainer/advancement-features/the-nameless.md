---
features:
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 7
      name: Looming Wings
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 corruption damage; I < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 corruption damage; I < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 corruption damage; I < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: If the Nameless's mentor is in the area, ability rolls against the mentor have a double bane until the start of their next turn.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 5 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 10
      name: Spew Death
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 corruption damage
            low: 11 corruption damage
            mid: 16 corruption damage
      sections:
        - label: Special
          text: The Nameless must be [winded](../../../rule/health/winded.md) to use this ability.
        - label: Effect
          text: Any living [minions](../../../rule/organization/minion.md) reduced to 0 [Stamina](../../../rule/health/stamina.md) by this ability regain all their [Stamina](../../../rule/health/stamina.md) and become corporeal [undead](../../../rule/keyword/undead.md) under the Nameless's control until the end of the Nameless's next turn, after which they are destroyed.
      target: Each enemy in the area
      usage: Main action
file_basename: the-nameless
file_dpath: monster/retainer/advancement-features
item_id: the-nameless
item_name: The Nameless Advancement Features
name: The Nameless Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/the-nameless
source: mcdm.monsters.v1
type: featureblock
---

> **Level 7 Retainer Advancement Ability**

> ❇️ **Looming Wings (Encounter)**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 corruption damage; I < WEAK [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 9 corruption damage; I < AVERAGE [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 12 corruption damage; I < STRONG [weakened](../../../condition/weakened.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** If the Nameless's mentor is in the area, ability rolls against the mentor have a double bane until the start of their next turn.

> **Level 10 Retainer Advancement Ability**

> ❇️ **Spew Death (Encounter)**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> **Special:** The Nameless must be [winded](../../../rule/health/winded.md) to use this ability.
>
> - **≤11:** 11 corruption damage
> - **12-16:** 16 corruption damage
> - **17+:** 21 corruption damage
>
> **Effect:** Any living [minions](../../../rule/organization/minion.md) reduced to 0 [Stamina](../../../rule/health/stamina.md) by this ability regain all their [Stamina](../../../rule/health/stamina.md) and become corporeal [undead](../../../rule/keyword/undead.md) under the Nameless's control until the end of the Nameless's next turn, after which they are destroyed.
