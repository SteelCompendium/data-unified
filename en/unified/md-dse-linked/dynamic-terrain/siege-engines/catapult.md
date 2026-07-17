---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a catapult can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The catapult is deactivated and can't be used.
            low: The creature accidentally activates the **Arcing Shot** ability.
            mid: The catapult is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - distance: 3 cube within 20
      icon: "\U0001F533"
      keywords:
        - '- Area'
        - Ranged
        - Weapon
      name: Arcing Shot
      power_roll:
        formula: + 2
        tiers:
            high: 12 damage; A < 1 push 2
            low: 5 damage
            mid: 9 damage; A < 0 push 1
      sections:
        - label: Effect
          text: Line of effect for this ability is an arc that can be traced over obstacles between the catapult and the target area. This ability can't be used again until the catapult is reloaded.
      target: Each creature and object in the area
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The catapult is reloaded, allowing **Arcing Shot** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Arcing Shot** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The catapult and the creature using this action move together up to 2 squares.
      target: '-'
      usage: Main action (Adjacent creature)
    - body: |-
        **Air Assault (+2 EV)** The side fielding the catapult has trained their forces to safely use the siege engine to launch them across the battlefield. As an adjacent creature main action, the catapult can be used to vertical push 10 any ally of size 1L or less. If the ally lands in an unoccupied space, they take no damage.

        **Flammable (+2 EV) Arcing Shot** deals fire damage, and the area of that ability is on fire until the end of the encounter. Any creature who enters the area for the first time in a round or starts their turn there takes 2 fire damage.
      icon: ⭐️
      name: Upgrades
file_basename: catapult
file_dpath: dynamic-terrain/siege-engines
flavor: This massive counterweighted engine hurls a heavy projectile for a devastating assault.
item_id: catapult
item_name: Catapult
level: 3
name: Catapult
role: Artillery
scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/catapult
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "10"
    - name: Stamina
      value: "50"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to a catapult can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The catapult is deactivated and can't be used.
            low: The creature accidentally activates the **Arcing Shot** ability.
            mid: The catapult is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - distance: 3 cube within 20
      icon: "\U0001F533"
      keywords:
        - '- Area'
        - Ranged
        - Weapon
      name: Arcing Shot
      power_roll:
        formula: + 2
        tiers:
            high: 12 damage; A < 1 push 2
            low: 5 damage
            mid: 9 damage; A < 0 push 1
      sections:
        - label: Effect
          text: Line of effect for this ability is an arc that can be traced over obstacles between the catapult and the target area. This ability can't be used again until the catapult is reloaded.
      target: Each creature and object in the area
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The catapult is reloaded, allowing **Arcing Shot** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Arcing Shot** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The catapult and the creature using this action move together up to 2 squares.
      target: '-'
      usage: Main action (Adjacent creature)
    - body: |-
        **Air Assault (+2 EV)** The side fielding the catapult has trained their forces to safely use the siege engine to launch them across the battlefield. As an adjacent creature main action, the catapult can be used to vertical push 10 any ally of size 1L or less. If the ally lands in an unoccupied space, they take no damage.

        **Flammable (+2 EV) Arcing Shot** deals fire damage, and the area of that ability is on fire until the end of the encounter. Any creature who enters the area for the first time in a round or starts their turn there takes 2 fire damage.
      icon: ⭐️
      name: Upgrades
flavor: This massive counterweighted engine hurls a heavy projectile for a devastating assault.
level: 3
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/catapult
    source: mcdm.monsters.v1
name: Catapult
role: Artillery
stats:
    - name: EV
      value: "10"
    - name: Stamina
      value: "50"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
```
