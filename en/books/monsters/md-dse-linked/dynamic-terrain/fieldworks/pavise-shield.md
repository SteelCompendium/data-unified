---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a pavise shield controlled by another creature can make a **Might test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The creature making the test grabs the shield and takes control of it.
            low: The creature controlling the shield retains control of it and can make an [opportunity attack](../../rule/combat/opportunity-attack.md) against the creature making the test.
            mid: The creature controlling the shield retains control of it.
    - body: |-
        While a creature has the pavise shield grabbed, they have [cover](../../rule/combat/cover.md) and take half damage from abilities whose line of effect extends through the shield. The pavise shield takes the other half of the damage.

        While a creature has a pavise shield grabbed, their speed is halved and they move the shield like a [grabbed](../../condition/grabbed.md) creature.
      icon: ⭐️
      name: Controlling the Shield
file_basename: pavise-shield
file_dpath: dynamic-terrain/fieldworks
flavor: A reinforced metal shield embedded in the ground acts as cover for the creature controlling it.
item_id: pavise-shield
item_name: Pavise Shield
level: 1
name: Pavise Shield
role: Defender
scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/pavise-shield
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "9"
    - name: Size
      value: 1M
terrain_type: Fortification
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a pavise shield controlled by another creature can make a **Might test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The creature making the test grabs the shield and takes control of it.
            low: The creature controlling the shield retains control of it and can make an [opportunity attack](../../rule/combat/opportunity-attack.md) against the creature making the test.
            mid: The creature controlling the shield retains control of it.
    - body: |-
        While a creature has the pavise shield grabbed, they have [cover](../../rule/combat/cover.md) and take half damage from abilities whose line of effect extends through the shield. The pavise shield takes the other half of the damage.

        While a creature has a pavise shield grabbed, their speed is halved and they move the shield like a [grabbed](../../condition/grabbed.md) creature.
      icon: ⭐️
      name: Controlling the Shield
flavor: A reinforced metal shield embedded in the ground acts as cover for the creature controlling it.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/pavise-shield
    source: mcdm.monsters.v1
name: Pavise Shield
role: Defender
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: "9"
    - name: Size
      value: 1M
terrain_type: Fortification
type: dynamic-terrain
```
