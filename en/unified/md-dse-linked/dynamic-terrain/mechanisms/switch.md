---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a switch can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The switch is deactivated and doesn't trigger.
            low: The creature triggers the switch.
            mid: The switch is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the switch uses a maneuver to trigger it.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The linked mechanism is activated. A switch automatically resets and can be triggered repeatedly.
    - body: '**Concealed (+1 EV)** The switch is hidden.'
      icon: ⭐️
      name: Upgrade
file_basename: switch
file_dpath: dynamic-terrain/mechanisms
flavor: Set into any surface, this mechanism acts as a trigger for another linked mechanism.
item_id: switch
item_name: Switch
level: 1
name: Switch
role: Support
scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/switch
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "3"
    - name: Size
      value: 1T
    - name: Link
      value: A switch is linked to another mechanism that it activates when triggered.
terrain_type: Trigger
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a switch can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The switch is deactivated and doesn't trigger.
            low: The creature triggers the switch.
            mid: The switch is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the switch uses a maneuver to trigger it.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The linked mechanism is activated. A switch automatically resets and can be triggered repeatedly.
    - body: '**Concealed (+1 EV)** The switch is hidden.'
      icon: ⭐️
      name: Upgrade
flavor: Set into any surface, this mechanism acts as a trigger for another linked mechanism.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/switch
    source: mcdm.monsters.v1
name: Switch
role: Support
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "3"
    - name: Size
      value: 1T
    - name: Link
      value: A switch is linked to another mechanism that it activates when triggered.
terrain_type: Trigger
type: dynamic-terrain
```
