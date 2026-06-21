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
          text: The mortar fires a shell straight upward, which hovers 3 squares up in the air and sheds light below it in a 3 cube. Enemies illuminated by this light can't [hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) or turn invisible and can't benefit from concealment or cover. At the start of the mortar's next turn, the shell explodes to deal damage to enemies in the area.
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
            high: 16 damage; I < STRONG [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends) and [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 8 damage; I < WEAK [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends
            mid: 12 damage; I < AVERAGE [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
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
            high: 13 damage; P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
            low: 6 damage; P < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
            mid: 9 damage; P < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
      sections:
        - label: Effect
          text: Until the start of the mortar's next turn, [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) made against the mortar or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them take a bane.
      target: Each enemy in the area
      usage: Main action
file_basename: dwarf-mortar
file_dpath: monster/retainer/advancement-features
item_id: dwarf-mortar
item_name: Dwarf Mortar Advancement Features
name: Dwarf Mortar Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/dwarf-mortar
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🔳 **Signal Shell (Encounter)**
>
> | **Area, Ranged, Weapon**  |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Special; see below** | **🎯 Each enemy in the area** |
>
> **Effect:** The mortar fires a shell straight upward, which hovers 3 squares up in the air and sheds light below it in a 3 cube. Enemies illuminated by this light can't [hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) or turn invisible and can't benefit from concealment or cover. At the start of the mortar's next turn, the shell explodes to deal damage to enemies in the area.
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 fire damage
> - **12-16:** 8 fire damage
> - **17+:** 11 fire damage

> **Level 10 Retainer Advancement Ability**

> 🔳 **Pacifier Shell (Encounter)**
>
> | **Area, Ranged, Weapon** |               **Main action** |
> |--------------------------|------------------------------:|
> | **📏 3 cube within 15**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; I < WEAK [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends
> - **12-16:** 12 damage; I < AVERAGE [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** 16 damage; I < STRONG [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends) and [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> **Level 7 Retainer Advancement Ability**

> 🔳 **Screaming Shell (Encounter)**
>
> | **Area, Weapon**            |               **Main action** |
> |-----------------------------|------------------------------:|
> | **📏 10 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage; P < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
> - **12-16:** 9 damage; P < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
> - **17+:** 13 damage; P < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened)
>
> **Effect:** Until the start of the mortar's next turn, [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) made against the mortar or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them take a bane.
