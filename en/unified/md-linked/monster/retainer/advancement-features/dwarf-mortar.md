---
features:
    - cost: Encounter
      distance: Special; see below
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      level: 4
      name: Signal Shell
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 fire damage
            low: 5 fire damage
            mid: 8 fire damage
      sections:
        - label: Effect
          text: The mortar fires a shell straight upward, which hovers 3 squares up in the air and sheds light below it in a 3 cube. Enemies illuminated by this light can't [hide](../../../feature/common/maneuvers/hide.md) or turn invisible and can't benefit from concealment or cover. At the start of the mortar's next turn, the shell explodes to deal damage to enemies in the area.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 15
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      level: 10
      name: Pacifier Shell
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; I < STRONG [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends) and [prone](../../../condition/prone.md)
            low: 8 damage; I < WEAK [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends
            mid: 12 damage; I < AVERAGE [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 10 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      level: 7
      name: Screaming Shell
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 13 damage; P < STRONG [frightened](../../../condition/frightened.md)
            low: 6 damage; P < WEAK [frightened](../../../condition/frightened.md)
            mid: 9 damage; P < AVERAGE [frightened](../../../condition/frightened.md)
      sections:
        - label: Effect
          text: Until the start of the mortar's next turn, [strikes](../../../rule/combat/strike.md) made against the mortar or any ally [adjacent](../../../rule/combat/adjacent.md) to them take a bane.
      target: Each enemy in the area
      usage: Main action
name: Dwarf Mortar Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/dwarf-mortar
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🔳 **Signal Shell (Encounter)**
>
> | **Area, Ranged, Weapon**  |               **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|------------------------------:|
> | **📏 Special; see below** | **🎯 Each enemy in the area** |
>
> **Effect:** The mortar fires a shell straight upward, which hovers 3 squares up in the air and sheds light below it in a 3 cube. Enemies illuminated by this light can't [hide](../../../feature/common/maneuvers/hide.md) or turn invisible and can't benefit from concealment or cover. At the start of the mortar's next turn, the shell explodes to deal damage to enemies in the area.
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 fire damage
> - **12-16:** 8 fire damage
> - **17+:** 11 fire damage

> **Level 10 Retainer Advancement Ability**

> 🔳 **Pacifier Shell (Encounter)**
>
> | **Area, Ranged, Weapon** |               **[Main action](../../../rule/combat/turn.md)** |
> |--------------------------|------------------------------:|
> | **📏 3 cube within 15**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; I < WEAK [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends
> - **12-16:** 12 damage; I < AVERAGE [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 16 damage; I < STRONG [dazed](../../../condition/dazed.md) ([save](../../../rule/general/saving-throw.md) ends) and [prone](../../../condition/prone.md)

> **Level 7 Retainer Advancement Ability**

> 🔳 **Screaming Shell (Encounter)**
>
> | **Area, Weapon**            |               **[Main action](../../../rule/combat/turn.md)** |
> |-----------------------------|------------------------------:|
> | **📏 10 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage; P < WEAK [frightened](../../../condition/frightened.md)
> - **12-16:** 9 damage; P < AVERAGE [frightened](../../../condition/frightened.md)
> - **17+:** 13 damage; P < STRONG [frightened](../../../condition/frightened.md)
>
> **Effect:** Until the start of the mortar's next turn, [strikes](../../../rule/combat/strike.md) made against the mortar or any ally [adjacent](../../../rule/combat/adjacent.md) to them take a bane.
