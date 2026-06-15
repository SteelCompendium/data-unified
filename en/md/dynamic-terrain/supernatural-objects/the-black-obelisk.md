---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the black obelisk can make a **Reason test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The obelisk is deactivated until the end of the encounter.
            low: The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
            mid: The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
    - body: A new round starts.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Your Fears Become Manifest** ability.
    - distance: 10 burst
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Your Fears Become Manifest
      power_roll:
        formula: + 2
        tiers:
            high: P < 3 [frightened](scc:mcdm.heroes.v1/condition/frightened), [slowed](scc:mcdm.heroes.v1/condition/slowed), and [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
            low: P < 1 [slowed](scc:mcdm.heroes.v1/condition/slowed) (EoT)
            mid: P < 2 [slowed](scc:mcdm.heroes.v1/condition/slowed) and [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
      sections:
        - label: Trigger
          text: A new round starts.
        - label: Effect
          text: The target is pushed 2 squares.
      target: Each enemy in the area
      usage: Free triggered action
flavor: A foreboding obelisk shaped of dark stone harrows the minds and spirits of those around it.
level: 3
name: The Black Obelisk
role: Controller
scc: mcdm.monsters.v1/dynamic-terrain.supernatural-objects/the-black-obelisk
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

A foreboding obelisk shaped of dark stone harrows the minds and spirits of those around it.

- **EV:** 20
- **Stamina:** 100
- **Size:** 2

> 🌀 **Deactivate**
>
> As a maneuver, a creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the black obelisk can make a **Reason test**.
>
> - **≤11:** The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
> - **12-16:** The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
> - **17+:** The obelisk is deactivated until the end of the encounter.

> ❕ **Activate**
>
> A new round starts.
>
> **Effect:** The **Your Fears Become Manifest** ability.

> ❗️ **Your Fears Become Manifest**
>
> | **Area, Magic** |     **Free triggered action** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** A new round starts.
>
> **Power Roll + 2:**
>
> - **≤11:** P < 1 [slowed](scc:mcdm.heroes.v1/condition/slowed) (EoT)
> - **12-16:** P < 2 [slowed](scc:mcdm.heroes.v1/condition/slowed) and [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
> - **17+:** P < 3 [frightened](scc:mcdm.heroes.v1/condition/frightened), [slowed](scc:mcdm.heroes.v1/condition/slowed), and [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
>
> **Effect:** The target is pushed 2 squares.
