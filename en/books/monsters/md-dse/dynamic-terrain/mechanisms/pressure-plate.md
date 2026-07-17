---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a pressure plate can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The pressure plate is deactivated and doesn't trigger.
            low: The creature triggers the pressure plate.
            mid: The pressure plate is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - body: The pressure plate is calibrated to be triggered by creatures or objects of a particular size. The pressure plate triggers when a creature or object of the appropriate size enters its area.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The linked mechanism is activated. A pressure plate automatically resets and can be triggered repeatedly.
    - body: '**Tripwire (−1 EV)** The pressure plate is a tripwire, which can trigger once and must be manually reset. A concealed tripwire can be discovered with an **easy Intuition test**.'
      icon: ⭐️
      name: Upgrade
    - body: The pressure plate is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
file_basename: pressure-plate
file_dpath: dynamic-terrain/mechanisms
flavor: This mechanism acts as a trigger for another linked mechanism, and is skillfully hidden from view in the floor.
item_id: pressure-plate
item_name: Pressure Plate
level: 1
name: Pressure Plate
role: Support
scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "2"
    - name: Stamina
      value: '-'
    - name: Size
      value: Any area
    - name: Typical Space
      value: One square, up to a 4 x 4-square area
    - name: Link
      value: A pressure plate is linked to another mechanism that it activates when triggered.
terrain_type: Trigger
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a pressure plate can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The pressure plate is deactivated and doesn't trigger.
            low: The creature triggers the pressure plate.
            mid: The pressure plate is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - body: The pressure plate is calibrated to be triggered by creatures or objects of a particular size. The pressure plate triggers when a creature or object of the appropriate size enters its area.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The linked mechanism is activated. A pressure plate automatically resets and can be triggered repeatedly.
    - body: '**Tripwire (−1 EV)** The pressure plate is a tripwire, which can trigger once and must be manually reset. A concealed tripwire can be discovered with an **easy Intuition test**.'
      icon: ⭐️
      name: Upgrade
    - body: The pressure plate is hidden until triggered or detected.
      icon: ⭐️
      name: Hidden
flavor: This mechanism acts as a trigger for another linked mechanism, and is skillfully hidden from view in the floor.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/pressure-plate
    source: mcdm.monsters.v1
name: Pressure Plate
role: Support
stats:
    - name: EV
      value: "2"
    - name: Stamina
      value: '-'
    - name: Size
      value: Any area
    - name: Typical Space
      value: One square, up to a 4 x 4-square area
    - name: Link
      value: A pressure plate is linked to another mechanism that it activates when triggered.
terrain_type: Trigger
type: dynamic-terrain
```
