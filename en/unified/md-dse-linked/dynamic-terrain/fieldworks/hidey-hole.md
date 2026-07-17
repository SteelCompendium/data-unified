---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a hidey-hole can make a **Might test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The hidey-hole collapses and can no longer be used until repaired.
            low: The creature is [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends).
            mid: The hidey-hole collapses but the creature is [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends).
    - body: A creature starts the encounter in the hidey-hole or ends their turn there.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The triggering creature can attempt to [hide](../../feature/common/maneuvers/hide.md) as a free triggered action.
    - body: '**Network (+1 EV per hidey-hole)** The hidey-hole is connected to a tunnel network. A creature familiar with the network can move from one hidey-hole to any space [adjacent](../../rule/combat/adjacent.md) to a connected hidey-hole if they have movement available equal to the straight-line distance to that space. A creature unfamiliar with the network can use a maneuver to make a **hard Intuition test** to discover a connected hidey-hole.'
      icon: ⭐️
      name: Upgrade
file_basename: hidey-hole
file_dpath: dynamic-terrain/fieldworks
flavor: A cavity in a floor, wall, or ceiling might hold hidden threats.
item_id: hidey-hole
item_name: Hidey-Hole
level: 1
name: Hidey-Hole
role: Ambusher
scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/hidey-hole
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: '-'
    - name: Size
      value: One or more squares
terrain_type: Fortification
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a hidey-hole can make a **Might test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The hidey-hole collapses and can no longer be used until repaired.
            low: The creature is [restrained](../../condition/restrained.md) ([save](../../rule/general/saving-throw.md) ends).
            mid: The hidey-hole collapses but the creature is [slowed](../../condition/slowed.md) ([save](../../rule/general/saving-throw.md) ends).
    - body: A creature starts the encounter in the hidey-hole or ends their turn there.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The triggering creature can attempt to [hide](../../feature/common/maneuvers/hide.md) as a free triggered action.
    - body: '**Network (+1 EV per hidey-hole)** The hidey-hole is connected to a tunnel network. A creature familiar with the network can move from one hidey-hole to any space [adjacent](../../rule/combat/adjacent.md) to a connected hidey-hole if they have movement available equal to the straight-line distance to that space. A creature unfamiliar with the network can use a maneuver to make a **hard Intuition test** to discover a connected hidey-hole.'
      icon: ⭐️
      name: Upgrade
flavor: A cavity in a floor, wall, or ceiling might hold hidden threats.
level: 1
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.fieldworks/hidey-hole
    source: mcdm.monsters.v1
name: Hidey-Hole
role: Ambusher
stats:
    - name: EV
      value: "1"
    - name: Stamina
      value: '-'
    - name: Size
      value: One or more squares
terrain_type: Fortification
type: dynamic-terrain
```
