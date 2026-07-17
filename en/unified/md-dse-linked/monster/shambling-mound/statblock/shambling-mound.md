---
agility: -1
ev: "84"
file_basename: shambling-mound
file_dpath: monster/shambling-mound/statblock
free_strike: 7
intuition: 1
item_id: shambling-mound
item_name: Shambling Mound
keywords:
    - Plant
    - Shambling Mound
level: 5
might: 4
name: Shambling Mound
organization: Solo
presence: 0
reason: 0
scc: mcdm.monsters.v1/monster.shambling-mound.statblock/shambling-mound
size: "3"
source: mcdm.monsters.v1
speed: 3
stability: 5
stamina: "400"
type: statblock
---

```ds-sb
agility: -1
ev: "84"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the shambling mound can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** The shambling mound can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The shambling mound has a vegetative sack on their body where they carry engulfed creatures. The sack has 30 [Stamina](../../../rule/health/stamina.md), damage immunity 5, and fire weakness 10. Destroying the sack frees creatures trapped by the shambling mound's Engulf ability. The shambling mound regrows a destroyed sack at the start of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Engulfing Sac
      type: feature
    - ability_type: Signature Ability
      distance: Melee 6
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; A < 3 [grabbed](../../../condition/grabbed.md)
          tier2: 16 damage; A < 4 [grabbed](../../../condition/grabbed.md)
          tier3: 19 damage; [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Vine Lash
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 6 burst
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 6 damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 7 damage; M < 4 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Seismic Slam
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 6
      effects:
        - effect: |-
            **Effect:** The target must be size 1L or smaller. The shambling mound reaches out with writhing vines, and if the target has A < 3, they are engulfed into the shambling mound's sack. If the target is [grabbed](../../../condition/grabbed.md) by the shambling mound, the [potency](../../../rule/character/potency.md) increases by 1. An engulfed creature is [restrained](../../../condition/restrained.md), takes 3 poison damage at the start of each turn, and can't take damage from abilities used from outside the sack. When the shambling mound moves, the engulfed creature moves with them. If the shambling mound dies or their sack is destroyed, each engulfed creature is freed and appears in an unoccupied space within 2 squares of the shambling mound.
            **2+ [Malice](../../../rule/monster/malice.md):** The shambling mound can engulf one additional target for each 2 [Malice](../../../rule/monster/malice.md) spent.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Engulf
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Each creature engulfed by the shambling mound takes 5 poison damage. The shambling mound gains 5 temporary [Stamina](../../../rule/health/stamina.md) for each creature who takes damage this way.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Leech
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 6
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; M < 2 [restrained](../../../condition/restrained.md) (EoT)
          tier2: 12 damage; M < 3 [restrained](../../../condition/restrained.md) (EoT)
          tier3: 15 damage; M < 4 [restrained](../../../condition/restrained.md) (EoT)
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Tether Down
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: While the shambling mound remains motionless, they are indistinguishable from ordinary vegetation.
      feature_type: trait
      icon: ⭐️
      name: False Appearance
      type: feature
    - effects:
        - effect: The area within 6 squares of the shambling mound is [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Frothing Flora
      type: feature
    - cost: Villain Action 1
      distance: 10 x 2 line within 1
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage, [pull](../../../movement/forced-movement.md) 3
          tier2: 12 damage; [pull](../../../movement/forced-movement.md) 4; the target has poison weakness 3 until the end of the encounter
          tier3: 15 damage; [pull](../../../movement/forced-movement.md) 6; the target has poison weakness 5 until the end of the encounter
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: Ravenous Overgrowth
      target: Each creature in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Melee 6
      effects:
        - effect: '**Effect:** The shambling mound uses Engulf against each target without spending [Malice](../../../rule/monster/malice.md).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Melee
      name: Composting
      target: Each enemy
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Self
      effects:
        - effect: '**Effect:** The shambling mound rips themself apart, exposing the crux of magic holding them together. The distance of the shambling mound''s melee abilities increases to melee 10, the creature has a double edge on power rolls, and strikes made against them gain an edge.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Melee
      name: Exposed Crux
      target: Self
      type: feature
      usage: '-'
free_strike: 7
intuition: 1
keywords:
    - Plant
    - Shambling Mound
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.shambling-mound.statblock/shambling-mound
    source: mcdm.monsters.v1
might: 4
name: Shambling Mound
organization: Solo
presence: 0
reason: 0
role: ""
size: "3"
speed: 3
stability: 5
stamina: "400"
type: statblock
```
