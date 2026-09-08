---
agility: 2
ev: "3"
file_basename: war-dog-crucibite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
immunities:
    - Fire 2
intuition: 0
item_id: war-dog-crucibite
item_name: War Dog Crucibite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 0
name: War Dog Crucibite
organization: Horde
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-crucibite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: 5 x 1 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 fire damage
          tier2: 4 fire damage
          tier3: 5 fire damage
        - effect: The area is covered in sticky fire until the start of the crucibite's next turn. Any creature who enters the area for the first time in a round or starts their turn there takes 2 fire damage.
          name: Effect
        - cost: 3 Malice
          effect: The area becomes a 10 x 1 line, and if any ally of the crucibite is in the area when it is created, the ability deals an extra 2 damage to each target.
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Flamebelcher
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: If the target has a loyalty collar, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Posthumous Promotion
      target: One war dog
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the crucibite is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 2
immunities:
    - Fire 2
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-crucibite
    source: mcdm.monsters.v1
might: 0
name: War Dog Crucibite
organization: Horde
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "10"
type: statblock
```
