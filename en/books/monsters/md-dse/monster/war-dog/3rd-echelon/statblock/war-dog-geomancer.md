---
agility: 1
ev: "10"
file_basename: war-dog-geomancer
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
intuition: 4
item_id: war-dog-geomancer
item_name: War Dog Geomancer
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
might: 2
movement: Burrow
name: War Dog Geomancer
organization: Horde
presence: 2
reason: 4
role: Controller
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-geomancer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "45"
type: statblock
---

```ds-sb
agility: 1
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 7 x 2 line within 10
      effects:
        - roll: Power Roll + 4
          tier1: 3 damage; M < 2 [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) (see effect)
          tier2: 6 damage; M < 3 [push](scc.v1:mcdm.heroes.v1/movement/forced-movement)
          tier3: 8 damage; M < 4 [push](scc.v1:mcdm.heroes.v1/movement/forced-movement), [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Earthwave
      target: Each creature in the area
      type: feature
      usage: Main action
    - distance: 5 wall within 10
      effects:
        - effect: '**Effect:** The geomancer raises a wall of stone set with viewing gaps. Creatures have line of effect through the wall while [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to it.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Siegeworks
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: The geomancer is always surrounded by a 2 aura of swirling dust and earthen debris. The geomancer and any ally in the area have concealment.
      feature_type: trait
      icon: ⭐️
      name: Dust Cloud
      type: feature
    - effects:
        - effect: When the geomancer is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-geomancer
    source: mcdm.monsters.v1
might: 2
movement: Burrow
name: War Dog Geomancer
organization: Horde
presence: 2
reason: 4
role: Controller
size: 1M
speed: 5
stability: 3
stamina: "45"
type: statblock
```
