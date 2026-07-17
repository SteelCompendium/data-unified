---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a portcullis can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The portcullis is deactivated and doesn't trigger.
            low: The creature triggers the portcullis and is affected as if in its area.
            mid: The portcullis is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - body: A [pressure plate](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate), [switch](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/switch), or other linked trigger is activated.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Heavy Gate** ability.
    - distance: Special
      icon: ❗️
      keywords:
        - Area
        - Weapon
      name: Heavy Gate
      power_roll:
        formula: + 2
        tiers:
            high: 10 damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 3 damage; slide 1, ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)
            mid: 7 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Trigger
          text: A [pressure plate](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate), [switch](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/switch), or other linked trigger is activated.
        - label: Special
          text: The area of this ability is the area directly beneath the portcullis when it falls.
        - label: Effect
          text: The portcullis blocks movement from one side of it to the other. A target slid by the portcullis ends up on one side of it or the other (choose randomly). The portcullis must be manually reset.
      target: Each creature and object in the area
      usage: Free triggered action
    - body: The portcullis is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
file_basename: portcullis
file_dpath: dynamic-terrain/mechanisms
flavor: A portcullis is hidden in the ceiling of a passage or choke point, waiting to drop when activated.
item_id: portcullis
item_name: Portcullis
level: 3
name: Portcullis
role: Ambusher
scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/portcullis
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "4"
    - name: Stamina
      value: 9 per square
    - name: Size
      value: The area of the corridor to be blocked
    - name: Typical Space
      value: 2 x 1-square area, up to a 4 x 2-square area
terrain_type: Trap
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a portcullis can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The portcullis is deactivated and doesn't trigger.
            low: The creature triggers the portcullis and is affected as if in its area.
            mid: The portcullis is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - body: A [pressure plate](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate), [switch](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/switch), or other linked trigger is activated.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Heavy Gate** ability.
    - distance: Special
      icon: ❗️
      keywords:
        - Area
        - Weapon
      name: Heavy Gate
      power_roll:
        formula: + 2
        tiers:
            high: 10 damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 3 damage; slide 1, ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability)
            mid: 7 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Trigger
          text: A [pressure plate](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate), [switch](scc.v1:mcdm.monsters.v1/dynamic-terrain.mechanisms/switch), or other linked trigger is activated.
        - label: Special
          text: The area of this ability is the area directly beneath the portcullis when it falls.
        - label: Effect
          text: The portcullis blocks movement from one side of it to the other. A target slid by the portcullis ends up on one side of it or the other (choose randomly). The portcullis must be manually reset.
      target: Each creature and object in the area
      usage: Free triggered action
    - body: The portcullis is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
flavor: A portcullis is hidden in the ceiling of a passage or choke point, waiting to drop when activated.
level: 3
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/portcullis
    source: mcdm.monsters.v1
name: Portcullis
role: Ambusher
stats:
    - name: EV
      value: "4"
    - name: Stamina
      value: 9 per square
    - name: Size
      value: The area of the corridor to be blocked
    - name: Typical Space
      value: 2 x 1-square area, up to a 4 x 2-square area
terrain_type: Trap
type: dynamic-terrain
```
