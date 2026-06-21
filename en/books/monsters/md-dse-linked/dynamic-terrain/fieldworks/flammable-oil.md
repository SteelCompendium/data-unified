---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a patch of flammable oil can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The oil is rendered safe and can't be ignited.
            low: The creature ignites the oil and is affected as if in its area.
            mid: The oil temporarily ignites before safely burning out, and the creature takes 3 fire damage and is burning ([save](../../rule/general/saving-throw.md) ends).
    - body: A creature or object in a square of oil takes fire damage, or a creature or object enters a square of burning oil or starts their turn there.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The triggering creature or object takes 3 fire damage and is burning ([save](../../rule/general/saving-throw.md) ends). A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.
    - body: '**Concealed Oil (+1 EV)** The oil is hidden until it ignites.'
      icon: ⭐️
      name: Upgrade
    - body: Allies who have weapons are equipped with torches. Any ally can use a maneuver to throw a torch up to 5 squares and ignite the flammable oil.
      icon: ⭐️
      name: Allied Awareness
file_basename: flammable-oil
file_dpath: dynamic-terrain/fieldworks
flavor: A patch of flammable oil or pitch on the ground is ready to be ignited.
item_id: flammable-oil
item_name: Flammable Oil
level: 1
name: Flammable Oil
role: Ambusher
scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/flammable-oil
source: mcdm.monsters.v1
stats:
    - name: EV
      value: 2 per 10 x 10 patch
    - name: Stamina
      value: '-'
    - name: Size
      value: One or more squares
terrain_type: Trap
type: dynamic-terrain
---

A patch of flammable oil or pitch on the ground is ready to be ignited.

- **EV:** 2 per 10 x 10 patch
- **Stamina:** -
- **Size:** One or more squares

> 🌀 **Deactivate**
>
> As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a patch of flammable oil can make an **Agility test**.
>
> - **≤11:** The creature ignites the oil and is affected as if in its area.
> - **12-16:** The oil temporarily ignites before safely burning out, and the creature takes 3 fire damage and is burning ([save](../../rule/general/saving-throw.md) ends).
> - **17+:** The oil is rendered safe and can't be ignited.

> ❕ **Activate**
>
> A creature or object in a square of oil takes fire damage, or a creature or object enters a square of burning oil or starts their turn there.
>
> **Effect:** The triggering creature or object takes 3 fire damage and is burning ([save](../../rule/general/saving-throw.md) ends). A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

> ⭐️ **Upgrade**
>
> **Concealed Oil (+1 EV)** The oil is hidden until it ignites.

> ⭐️ **Allied Awareness**
>
> Allies who have weapons are equipped with torches. Any ally can use a maneuver to throw a torch up to 5 squares and ignite the flammable oil.
