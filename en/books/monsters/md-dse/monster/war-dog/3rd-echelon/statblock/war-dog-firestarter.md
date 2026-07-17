---
agility: 2
ev: "10"
file_basename: war-dog-firestarter
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
immunities:
    - Fire 8
intuition: 4
item_id: war-dog-firestarter
item_name: War Dog Firestarter
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
might: 0
name: War Dog Firestarter
organization: Horde
presence: 1
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-firestarter
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "45"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 10 x 1 line within 1
      effects:
        - roll: Power Roll + 4
          tier1: 3 fire damage; A < 2 the target is seared (save ends)
          tier2: 6 fire damage; A < 3 the target is seared (save ends)
          tier3: 8 fire damage; A < 4 the target is seared (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Twin Flamebelchers
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 2 fire damage
          tier2: 4 fire damage; A < 3 the target is seared (save ends)
          tier3: 6 fire damage; A < 4 the target is seared (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Enflame
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the firestarter is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
immunities:
    - Fire 8
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-firestarter
    source: mcdm.monsters.v1
might: 0
name: War Dog Firestarter
organization: Horde
presence: 1
reason: 3
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "45"
type: statblock
```
