---
agility: 2
ev: "48"
file_basename: castellan-hoplon
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 10
immunities:
    - Damage 3
intuition: 3
item_id: castellan-hoplon
item_name: Castellan Hoplon
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 5
name: Castellan Hoplon
organization: Elite
presence: 4
reason: 4
role: Defender
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/castellan-hoplon
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "260"
type: statblock
---

```ds-sb
agility: 2
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage
          tier2: 20 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 24 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Inspiring Strike
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Ranged 15
      effects:
        - effect: '**Effect:** A 10-square-tall tower made of black stone shimmers into being in an unoccupied space that is 5 squares on a side. The tower has three floors, an entrance in the middle of each side on the ground floor, and a crenelated rooftop. Any war dog inside or [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the tower has damage immunity 2 and regains 5 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) at the start of each of their turns, and war dogs inside the tower can observe through and have line of effect through its walls. This ability can be used only once per encounter.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Summon the Onyx Tower
      target: Special
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 5
          tier1: R < 3 taunted (EoT)
          tier2: R < 4 taunted (EoT)
          tier3: R < 5 taunted (EoT)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Shield Warden
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** An enemy within 10 squares targets an ally with an ability.
            **Effect:** Hoplon [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the enemy and becomes the new target of the ability. He can then make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the enemy, and if that enemy has R < 4 they are taunted until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: Timely Intervention
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Each ally within 3 squares of Hoplon has cover and damage immunity 2.
      feature_type: trait
      icon: ⭐️
      name: Hold the Line
      type: feature
    - effects:
        - effect: The first time in an encounter that Hoplon is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), he instead has 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and gains damage immunity 10 until the end of his next turn. When Hoplon is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) again, each ally within 5 squares of him gains damage immunity 3 and deals an extra 5 damage on strikes, all until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Last Stand
      type: feature
free_strike: 10
immunities:
    - Damage 3
intuition: 3
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/castellan-hoplon
    source: mcdm.monsters.v1
might: 5
name: Castellan Hoplon
organization: Elite
presence: 4
reason: 4
role: Defender
size: 1M
speed: 5
stability: 3
stamina: "260"
type: statblock
```
