---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to an iron dragon can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The iron dragon is deactivated and can't be used.
            low: The creature accidentally activates the **Gout of Flame** ability.
            mid: The iron dragon is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - distance: 8 x 2 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Gout of Flame
      power_roll:
        formula: + 2
        tiers:
            high: 13 fire damage; A < 2 the target is burning ([save](../../rule/general/saving-throw.md) ends)
            low: 6 fire damage; A < 0 the target is burning ([save](../../rule/general/saving-throw.md) ends)
            mid: 10 fire damage; A < 1 the target is burning ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. This ability can't be used again until the iron dragon is reloaded.
      target: Each creature and object in the area
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The iron dragon is reloaded, allowing **Gout of Flame** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Gout of Flame** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The iron dragon and the creature using this action move together up to 2 squares.
      target: '-'
      usage: Main action (Adjacent creature)
file_basename: iron-dragon
file_dpath: dynamic-terrain/siege-engines
flavor: A massive metal device uses a bellows system and liquid fuel to shoot out gouts of flame.
item_id: iron-dragon
item_name: Iron Dragon
level: 4
name: Iron Dragon
role: Artillery
scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/iron-dragon
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "12"
    - name: Stamina
      value: "60"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](../../rule/combat/adjacent.md) to an iron dragon can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The iron dragon is deactivated and can't be used.
            low: The creature accidentally activates the **Gout of Flame** ability.
            mid: The iron dragon is deactivated but the creature is [slowed](../../condition/slowed.md) (EoT).
    - distance: 8 x 2 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Gout of Flame
      power_roll:
        formula: + 2
        tiers:
            high: 13 fire damage; A < 2 the target is burning ([save](../../rule/general/saving-throw.md) ends)
            low: 6 fire damage; A < 0 the target is burning ([save](../../rule/general/saving-throw.md) ends)
            mid: 10 fire damage; A < 1 the target is burning ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. This ability can't be used again until the iron dragon is reloaded.
      target: Each creature and object in the area
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The iron dragon is reloaded, allowing **Gout of Flame** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Gout of Flame** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The iron dragon and the creature using this action move together up to 2 squares.
      target: '-'
      usage: Main action (Adjacent creature)
flavor: A massive metal device uses a bellows system and liquid fuel to shoot out gouts of flame.
level: 4
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/iron-dragon
    source: mcdm.monsters.v1
name: Iron Dragon
role: Artillery
stats:
    - name: EV
      value: "12"
    - name: Stamina
      value: "60"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
```
