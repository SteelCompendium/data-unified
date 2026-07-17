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
file_basename: quicksand
file_dpath: dynamic-terrain/environmental-hazards
flavor: When this patch of sand is stepped on, it is revealed to be a slurry saturated by water—and ready to draw creatures down to their doom.
item_id: quicksand
item_name: Quicksand
level: 3
name: Quicksand
role: Hexer
scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/quicksand
source: mcdm.monsters.v1
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

```ds-fb
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
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/quicksand
    source: mcdm.monsters.v1
name: Quicksand
role: Hexer
stats:
    - name: EV
      value: 3 per 10 x 10 patch
    - name: Stamina
      value: '-'
    - name: Size
      value: One or more squares
terrain_type: Hazard
type: dynamic-terrain
```
