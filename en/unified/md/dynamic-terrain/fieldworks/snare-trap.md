---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a snare trap can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The trap is deactivated and doesn't trigger.
            low: The creature triggers the trap and is affected as if in its space.
            mid: The trap is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - body: The snare trap is calibrated to be triggered by creatures or objects of a particular size or larger. The trap triggers when a creature or object of the appropriate size enters its space.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: A triggering creature or object ends their movement and is targeted by the **Snare** ability.
    - distance: Melee 0
      icon: ❗️
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Snare
      power_roll:
        formula: + 2
        tiers:
            high: 3 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: The target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square away from the snare.
            mid: 1 damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Trigger
          text: A creature or object of the appropriate size enters the trap's space.
        - label: Effect
          text: A creature [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way is vertical pulled 2 squares and suspended in the air by the snare line. On a successful [save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw), the snare is cut or breaks and the creature falls to the ground. The snare must be manually reset.
      target: The triggering creature or object
      usage: Free triggered action
    - body: '**Net Trap (+1 EV)** The snare becomes a net that can wrap up multiple targets. The net has 3 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and fills an area of 3 squares by 3 squares. The Snare ability loses its existing keywords, gains the Area keyword, and targets each creature or object in the area. The trap can be triggered by a target moving through one specific square, or by requiring multiple squares to be moved through. Any creature who makes their [save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) to end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) effect ends that effect for all targets, who all fall to the ground.'
      icon: ⭐️
      name: Upgrade
    - body: The snare trap is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
flavor: A rope snare is set to grab a target, leaving them hanging upside down.
level: 1
name: Snare Trap
role: Ambusher
scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/snare-trap
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "1"
    - name: Size
      value: 1S
terrain_type: Trap
type: dynamic-terrain
---

A rope snare is set to grab a target, leaving them hanging upside down.

- **EV:** 1
- **Stamina:** 1
- **Size:** 1S

> 🌀 **Deactivate**
>
> As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a snare trap can make an **Agility test**.
>
> - **≤11:** The creature triggers the trap and is affected as if in its space.
> - **12-16:** The trap is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
> - **17+:** The trap is deactivated and doesn't trigger.

> ❕ **Activate**
>
> The snare trap is calibrated to be triggered by creatures or objects of a particular size or larger. The trap triggers when a creature or object of the appropriate size enters its space.
>
> **Effect:** A triggering creature or object ends their movement and is targeted by the **Snare** ability.

> ❗️ **Snare**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> |---------------------------|-----------------------------------------:|
> | **📏 Melee 0**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object of the appropriate size enters the trap's space.
>
> **Power Roll + 2:**
>
> - **≤11:** The target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square away from the snare.
> - **12-16:** 1 damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** 3 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
>
> **Effect:** A creature [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way is vertical pulled 2 squares and suspended in the air by the snare line. On a successful [save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw), the snare is cut or breaks and the creature falls to the ground. The snare must be manually reset.

> ⭐️ **Upgrade**
>
> **Net Trap (+1 EV)** The snare becomes a net that can wrap up multiple targets. The net has 3 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and fills an area of 3 squares by 3 squares. The Snare ability loses its existing keywords, gains the Area keyword, and targets each creature or object in the area. The trap can be triggered by a target moving through one specific square, or by requiring multiple squares to be moved through. Any creature who makes their [save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) to end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) effect ends that effect for all targets, who all fall to the ground.

> ⭐️ **Hidden**
>
> The snare trap is hidden until triggered or detected.
