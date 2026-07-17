---
agility: 4
ev: "10"
file_basename: war-dog-aerocite
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
intuition: 3
item_id: war-dog-aerocite
item_name: War Dog Aerocite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
might: 0
movement: Fly
name: War Dog Aerocite
organization: Horde
presence: 1
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-aerocite
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 4
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage
          tier2: 10 damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 12 damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Dive Bomb
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 3 cube within 5
      effects:
        - roll: Power Roll + 4
          tier1: 2 acid damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier2: 4 acid damage; M < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 6 acid damage; M < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Caustic Paste Bomb
      target: Each creature or object in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: If the aerocite moves 5 or more squares on their turn, strikes made against them take a bane until the start of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Jetwing Agility
      type: feature
    - effects:
        - effect: When the aerocite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
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
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-aerocite
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: War Dog Aerocite
organization: Horde
presence: 1
reason: 1
role: Harrier
size: 1M
speed: 8
stability: 0
stamina: "50"
type: statblock
```
