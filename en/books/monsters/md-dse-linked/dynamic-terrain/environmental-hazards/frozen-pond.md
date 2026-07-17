---
features:
    - body: Destroying a square of the frozen pond turns the square into shallow icy water.
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature or object enters a square of the frozen pond without [shifting](../../movement/shifting.md).
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Slippery Surface** ability.
    - distance: Melee 0
      icon: ❗️
      keywords:
        - Melee
        - Strike
      name: Slippery Surface
      power_roll:
        formula: + 2
        tiers:
            high: Push 3 in the direction the target was moving; A < 2 [prone](../../condition/prone.md) and can't stand ([save](../../rule/general/saving-throw.md) ends)
            low: Push 1 in the direction the target was moving
            mid: Push 2 in the direction the target was moving; A < 1 [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object enters a square of the frozen pond without [shifting](../../movement/shifting.md).
        - label: Effect
          text: The triggering creature's movement ends, then they are [force moved](../../movement/forced-movement.md). If the target triggered this ability by being [force moved](../../movement/forced-movement.md), this ability gains an edge and any remaining [forced movement](../../movement/forced-movement.md) distance is added to the ability's [forced movement](../../movement/forced-movement.md). The ability's [forced movement](../../movement/forced-movement.md) doesn't trigger the ability again.
      target: The triggering creature or object
      usage: Free triggered action
    - body: |-
        **Thin Ice (+1 EV)** The ice covering the pond is thin and the water is deeper. Whenever a creature or object enters or falls [prone](../../condition/prone.md) in a square of the frozen pond, that square is destroyed and replaced with icy water. The **Icy Water** ability replaces **Slippery Surface**.

        Any creature who starts their turn in the icy water takes 1 cold damage. If the water is deep enough, a creature can swim beneath the surface of the frozen pond, but takes this cold damage while doing so.
      icon: ⭐️
      name: Upgrade
file_basename: frozen-pond
file_dpath: dynamic-terrain/environmental-hazards
flavor: A shallow, frozen patch of water features ice thick enough that it won't break, but its surface is slick and treacherous to navigate.
item_id: frozen-pond
item_name: Frozen Pond
level: 1
name: Frozen Pond
role: Hexer
scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/frozen-pond
source: mcdm.monsters.v1
stats:
    - name: EV
      value: 1 per 10 x 10 pond
    - name: Stamina
      value: 3 per square
    - name: Size
      value: One or more squares of [difficult terrain](../../movement/difficult-terrain.md)
    - name: Immunity
      value: 5 to all damage except fire damage
terrain_type: Hazard
type: dynamic-terrain
---

```ds-fb
features:
    - body: Destroying a square of the frozen pond turns the square into shallow icy water.
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature or object enters a square of the frozen pond without [shifting](../../movement/shifting.md).
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Slippery Surface** ability.
    - distance: Melee 0
      icon: ❗️
      keywords:
        - Melee
        - Strike
      name: Slippery Surface
      power_roll:
        formula: + 2
        tiers:
            high: Push 3 in the direction the target was moving; A < 2 [prone](../../condition/prone.md) and can't stand ([save](../../rule/general/saving-throw.md) ends)
            low: Push 1 in the direction the target was moving
            mid: Push 2 in the direction the target was moving; A < 1 [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object enters a square of the frozen pond without [shifting](../../movement/shifting.md).
        - label: Effect
          text: The triggering creature's movement ends, then they are [force moved](../../movement/forced-movement.md). If the target triggered this ability by being [force moved](../../movement/forced-movement.md), this ability gains an edge and any remaining [forced movement](../../movement/forced-movement.md) distance is added to the ability's [forced movement](../../movement/forced-movement.md). The ability's [forced movement](../../movement/forced-movement.md) doesn't trigger the ability again.
      target: The triggering creature or object
      usage: Free triggered action
    - body: |-
        **Thin Ice (+1 EV)** The ice covering the pond is thin and the water is deeper. Whenever a creature or object enters or falls [prone](../../condition/prone.md) in a square of the frozen pond, that square is destroyed and replaced with icy water. The **Icy Water** ability replaces **Slippery Surface**.

        Any creature who starts their turn in the icy water takes 1 cold damage. If the water is deep enough, a creature can swim beneath the surface of the frozen pond, but takes this cold damage while doing so.
      icon: ⭐️
      name: Upgrade
flavor: A shallow, frozen patch of water features ice thick enough that it won't break, but its surface is slick and treacherous to navigate.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.environmental-hazards/frozen-pond
    source: mcdm.monsters.v1
name: Frozen Pond
role: Hexer
stats:
    - name: EV
      value: 1 per 10 x 10 pond
    - name: Stamina
      value: 3 per square
    - name: Size
      value: One or more squares of [difficult terrain](../../movement/difficult-terrain.md)
    - name: Immunity
      value: 5 to all damage except fire damage
terrain_type: Hazard
type: dynamic-terrain
```
