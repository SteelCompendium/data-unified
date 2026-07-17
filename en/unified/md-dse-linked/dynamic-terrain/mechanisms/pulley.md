---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a pulley can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The pulley is deactivated and doesn't trigger.
            low: The creature triggers the pulley.
            mid: The pulley is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the pulley uses a maneuver to release the pulley.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The triggering creature is lifted to the top of the structure the pulley is attached to. The pulley must be manually reset.
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the pulley can climb its ropes with an **easy Agility test** to ascend to the top of the structure it's attached to.
      icon: ⭐️
      name: Climbable
    - body: '**Looped Chain (+1 EV)** Instead of a rope and pulley, the system uses a counterweighted looped chain. A looped chain automatically resets and can be triggered repeatedly.'
      icon: ⭐️
      name: Upgrade
file_basename: pulley
file_dpath: dynamic-terrain/mechanisms
flavor: A counterweighted pulley system can be used to quickly ascend to the top of a wall, scaffold, tower, or other structure.
item_id: pulley
item_name: Pulley
level: 1
name: Pulley
role: Support
scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/pulley
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "1"
    - name: Size
      value: 1S
terrain_type: Trigger
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a pulley can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The pulley is deactivated and doesn't trigger.
            low: The creature triggers the pulley.
            mid: The pulley is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the pulley uses a maneuver to release the pulley.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The triggering creature is lifted to the top of the structure the pulley is attached to. The pulley must be manually reset.
    - body: A creature [adjacent](../../rule/combat/adjacent.md) to the pulley can climb its ropes with an **easy Agility test** to ascend to the top of the structure it's attached to.
      icon: ⭐️
      name: Climbable
    - body: '**Looped Chain (+1 EV)** Instead of a rope and pulley, the system uses a counterweighted looped chain. A looped chain automatically resets and can be triggered repeatedly.'
      icon: ⭐️
      name: Upgrade
flavor: A counterweighted pulley system can be used to quickly ascend to the top of a wall, scaffold, tower, or other structure.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/pulley
    source: mcdm.monsters.v1
name: Pulley
role: Support
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "1"
    - name: Size
      value: 1S
terrain_type: Trigger
type: dynamic-terrain
```
