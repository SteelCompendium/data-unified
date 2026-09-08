---
features:
    - effects:
        - effect: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to the black obelisk can make a **Reason test**.
          tier1: The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
          tier2: The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
          tier3: The obelisk is deactivated until the end of the encounter.
      icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to the black obelisk can make a **Reason test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The obelisk is deactivated until the end of the encounter.
            low: The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
            mid: The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
    - body: A new round starts.
      effects:
        - effect: A new round starts.
        - effect: The **Your Fears Become Manifest** ability.
          name: Effect
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Your Fears Become Manifest** ability.
    - distance: 10 burst
      effects:
        - effect: A new round starts.
          name: Trigger
          roll: Power Roll + 2
          tier1: P < 1 [slowed](../../condition/slowed.md) (EoT)
          tier2: P < 2 [slowed](../../condition/slowed.md) and [weakened](../../condition/weakened.md) (EoT)
          tier3: P < 3 [frightened](../../condition/frightened.md), [slowed](../../condition/slowed.md), and [weakened](../../condition/weakened.md) (EoT)
        - effect: The target is pushed 2 squares.
          name: Effect
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Your Fears Become Manifest
      power_roll:
        formula: + 2
        tiers:
            high: P < 3 [frightened](../../condition/frightened.md), [slowed](../../condition/slowed.md), and [weakened](../../condition/weakened.md) (EoT)
            low: P < 1 [slowed](../../condition/slowed.md) (EoT)
            mid: P < 2 [slowed](../../condition/slowed.md) and [weakened](../../condition/weakened.md) (EoT)
      sections:
        - label: Trigger
          text: A new round starts.
        - label: Effect
          text: The target is pushed 2 squares.
      target: Each enemy in the area
      usage: Free triggered action
file_basename: the-black-obelisk
file_dpath: dynamic-terrain/supernatural-objects
flavor: A foreboding obelisk shaped of dark stone harrows the minds and spirits of those around it.
item_id: the-black-obelisk
item_name: The Black Obelisk
level: 3
name: The Black Obelisk
role: Controller
scc: mcdm.monsters.v1/dynamic-terrain.supernatural-objects/the-black-obelisk
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "20"
    - name: Stamina
      value: "100"
    - name: Size
      value: "2"
terrain_type: Relic
type: dynamic-terrain
---

```ds-fb
features:
    - effects:
        - effect: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to the black obelisk can make a **Reason test**.
          tier1: The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
          tier2: The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
          tier3: The obelisk is deactivated until the end of the encounter.
      icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to the black obelisk can make a **Reason test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The obelisk is deactivated until the end of the encounter.
            low: The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
            mid: The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
    - body: A new round starts.
      effects:
        - effect: A new round starts.
        - effect: The **Your Fears Become Manifest** ability.
          name: Effect
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Your Fears Become Manifest** ability.
    - distance: 10 burst
      effects:
        - effect: A new round starts.
          name: Trigger
          roll: Power Roll + 2
          tier1: P < 1 [slowed](../../condition/slowed.md) (EoT)
          tier2: P < 2 [slowed](../../condition/slowed.md) and [weakened](../../condition/weakened.md) (EoT)
          tier3: P < 3 [frightened](../../condition/frightened.md), [slowed](../../condition/slowed.md), and [weakened](../../condition/weakened.md) (EoT)
        - effect: The target is pushed 2 squares.
          name: Effect
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Your Fears Become Manifest
      power_roll:
        formula: + 2
        tiers:
            high: P < 3 [frightened](../../condition/frightened.md), [slowed](../../condition/slowed.md), and [weakened](../../condition/weakened.md) (EoT)
            low: P < 1 [slowed](../../condition/slowed.md) (EoT)
            mid: P < 2 [slowed](../../condition/slowed.md) and [weakened](../../condition/weakened.md) (EoT)
      sections:
        - label: Trigger
          text: A new round starts.
        - label: Effect
          text: The target is pushed 2 squares.
      target: Each enemy in the area
      usage: Free triggered action
flavor: A foreboding obelisk shaped of dark stone harrows the minds and spirits of those around it.
level: 3
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.supernatural-objects/the-black-obelisk
    source: mcdm.monsters.v1
name: The Black Obelisk
role: Controller
stats:
    - name: EV
      value: "20"
    - name: Stamina
      value: "100"
    - name: Size
      value: "2"
terrain_type: Relic
type: dynamic-terrain
```
