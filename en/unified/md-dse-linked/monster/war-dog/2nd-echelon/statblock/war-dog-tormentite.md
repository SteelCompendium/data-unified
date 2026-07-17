---
agility: 0
ev: "7"
file_basename: war-dog-tormentite
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: 3
item_id: war-dog-tormentite
item_name: War Dog Tormentite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
might: 0
name: War Dog Tormentite
organization: Horde
presence: 0
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-tormentite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 0
ev: "7"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 6 corruption damage
          tier2: 8 corruption damage; the target is marked (save ends)
          tier3: 9 corruption damage; the target is marked (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Mark of Agony
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 4 cube within 10
      effects:
        - roll: Power Roll + 3
          tier1: 2 corruption damage
          tier2: 4 corruption damage
          tier3: 5 corruption damage; one ally in the area can end one effect on them that can be ended by a [saving throw](../../../../rule/general/saving-throw.md), and can give that effect to one target
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Vortex of Pain
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: From the start of the encounter, the tormentite takes 1 damage at the start of each of their turns.
      feature_type: trait
      icon: ⭐️
      name: Persistent Pain
      type: feature
    - effects:
        - effect: When the tormentite is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
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
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-tormentite
    source: mcdm.monsters.v1
might: 0
name: War Dog Tormentite
organization: Horde
presence: 0
reason: 2
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
