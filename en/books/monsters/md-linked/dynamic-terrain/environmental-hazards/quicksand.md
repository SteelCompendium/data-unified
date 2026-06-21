---
features:
    - body: '-'
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature or object enters the quicksand or starts their turn there.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Grasping Depths** ability.
    - distance: Melee 0
      icon: ❗️
      keywords:
        - Melee
        - Strike
      name: Grasping Depths
      power_roll:
        formula: + 2
        tiers:
            high: M < 2 [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends)
            low: M < 0 [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends)
            mid: M < 1 [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object enters the quicksand or starts their turn there.
        - label: Effect
          text: This ability takes a bane if a triggering creature [shifted](../../movement/shifting.md) into the quicksand. A character who starts their turn [restrained](../../condition/restrained.md) this way is [suffocating](../../rule/health/suffocating.md).
      target: The triggering creature or object
      usage: Free triggered action
    - body: The quicksand is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
flavor: When this patch of sand is stepped on, it is revealed to be a slurry saturated by water—and ready to draw creatures down to their doom.
level: 3
name: Quicksand
role: Hexer
scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/quicksand
stats:
    - name: EV
      value: 3 per 10 x 10 patch
    - name: Stamina
      value: '-'
    - name: Size
      value: One or more squares
terrain_type: Hazard
type: dynamic-terrain
---

When this patch of sand is stepped on, it is revealed to be a slurry saturated by water—and ready to draw creatures down to their doom.

- **EV:** 3 per 10 x 10 patch
- **Stamina:** -
- **Size:** One or more squares

> 🌀 **Deactivate**
>
> -

> ❕ **Activate**
>
> A creature or object enters the quicksand or starts their turn there.
>
> **Effect:** The **Grasping Depths** ability.

> ❗️ **Grasping Depths**
>
> | **Melee, Strike** |                **Free triggered action** |
> |-------------------|-----------------------------------------:|
> | **📏 Melee 0**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters the quicksand or starts their turn there.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends)
> - **12-16:** M < 1 [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends)
> - **17+:** M < 2 [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends)
>
> **Effect:** This ability takes a bane if a triggering creature [shifted](../../movement/shifting.md) into the quicksand. A character who starts their turn [restrained](../../condition/restrained.md) this way is [suffocating](../../rule/health/suffocating.md).

> ⭐️ **Hidden**
>
> The quicksand is hidden until triggered or detected.
