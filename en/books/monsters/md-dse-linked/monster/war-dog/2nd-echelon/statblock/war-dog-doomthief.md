---
agility: -1
ev: "7"
file_basename: war-dog-doomthief
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: 3
item_id: war-dog-doomthief
item_name: War Dog Doomthief
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
might: 3
name: War Dog Doomthief
organization: Horde
presence: 1
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-doomthief
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "40"
type: statblock
---

```ds-sb
agility: -1
ev: "7"
features:
    - ability_type: Signature Ability
      distance: 10 x 3 line within 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage; [push](../../../../movement/forced-movement.md) 1
          tier2: 5 damage; [push](../../../../movement/forced-movement.md) 3
          tier3: 6 damage; [push](../../../../movement/forced-movement.md) 5; A < 3 [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Ripper Shrikegun
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The doomthief emits a 3 aura of warped fate that blocks line of effect for any enemy ability that doesn't include them as a target.
      feature_type: trait
      icon: ⭐️
      name: Doom Magnet
      type: feature
    - cost: 4 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The doomthief has damage immunity 4 and the size of the aura from their Doom Magnet trait increases by 3, both until the start of their next turn.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Expanding Doom
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the doomthief is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
intuition: 3
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-doomthief
    source: mcdm.monsters.v1
might: 3
name: War Dog Doomthief
organization: Horde
presence: 1
reason: 0
role: Defender
size: 1L
speed: 5
stability: 2
stamina: "40"
type: statblock
```
