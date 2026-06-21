---
features:
    - body: Each square of plants must be individually destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without [shifting](../../movement/shifting.md).
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Sleep Spores** ability.
    - distance: Melee 0
      icon: ❗️
      keywords:
        - Magic
        - Melee
        - Strike
      name: Sleep Spores
      power_roll:
        formula: + 2
        tiers:
            high: M < 2 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
            low: M < 0 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
            mid: M < 1 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without [shifting](../../movement/shifting.md).
        - label: Effect
          text: While [dazed](../../condition/dazed.md) this way, a target who starts their turn in the area of the toxic plants falls [prone](../../condition/prone.md) and can't stand.
      target: The triggering creature
      usage: Free triggered action
    - body: |-
        **Poisonous Spores (+2 EV)** Any creature [dazed](../../condition/dazed.md) by this hazard takes 1d6 poison damage at the start of each of their turns.

        **Carnivorous Plants (+2 EV)** The plants are carnivorous and attempt to slowly digest any creature who falls among them. Any creature who starts their turn [prone](../../condition/prone.md) in the area takes 4 acid damage.
      icon: ⭐️
      name: Upgrades
file_basename: toxic-plants
file_dpath: dynamic-terrain/environmental-hazards
flavor: Colorful mushrooms or lovely flowering plants release a cloud of spores or pollen when disturbed, causing creatures to fall into a magical slumber.
item_id: toxic-plants
item_name: Toxic Plants
level: 2
name: Toxic Plants
role: Hexer
scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/toxic-plants
source: mcdm.monsters.v1
stats:
    - name: EV
      value: 2 per 10 x 10 field
    - name: Stamina
      value: 3 per square
    - name: Size
      value: One or more squares
terrain_type: Hazard
type: dynamic-terrain
---

Colorful mushrooms or lovely flowering plants release a cloud of spores or pollen when disturbed, causing creatures to fall into a magical slumber.

- **EV:** 2 per 10 x 10 field
- **Stamina:** 3 per square
- **Size:** One or more squares

> 🌀 **Deactivate**
>
> Each square of plants must be individually destroyed.

> ❕ **Activate**
>
> A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without [shifting](../../movement/shifting.md).
>
> **Effect:** The **Sleep Spores** ability.

> ❗️ **Sleep Spores**
>
> | **Magic, Melee, Strike** |      **Free triggered action** |
> |--------------------------|-------------------------------:|
> | **📏 Melee 0**           | **🎯 The triggering creature** |
>
> **Trigger:** A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without [shifting](../../movement/shifting.md).
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
> - **12-16:** M < 1 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
> - **17+:** M < 2 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
>
> **Effect:** While [dazed](../../condition/dazed.md) this way, a target who starts their turn in the area of the toxic plants falls [prone](../../condition/prone.md) and can't stand.

> ⭐️ **Upgrades**
>
> **Poisonous Spores (+2 EV)** Any creature [dazed](../../condition/dazed.md) by this hazard takes 1d6 poison damage at the start of each of their turns.
>
> **Carnivorous Plants (+2 EV)** The plants are carnivorous and attempt to slowly digest any creature who falls among them. Any creature who starts their turn [prone](../../condition/prone.md) in the area takes 4 acid damage.
