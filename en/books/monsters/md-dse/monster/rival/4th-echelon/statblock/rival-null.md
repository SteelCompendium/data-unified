---
agility: 5
ev: "48"
file_basename: rival-null
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 5
item_id: rival-null
item_name: Rival Null
keywords:
    - Humanoid
    - Rival
level: 10
might: 3
name: Rival Null
organization: Elite
presence: 0
reason: 4
role: Harrier
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-null
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "240"
type: statblock
---

```ds-sb
agility: 5
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares; A < 3 10 damage
          tier2: 20 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 5 squares; A < 4 15 damage
          tier3: 24 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 6 squares; A < 5 19 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Kinetic Danse
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 13 damage; R < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 17 damage; R < 4 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 20 damage; R < 5 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Incapacitate
      target: Two creatures or objects
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time each round that the null is targeted by a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), it takes a bane and the null halves the damage from it. The creature making the strike takes 10 damage.
      feature_type: trait
      icon: ⭐️
      name: Energy Conservation
      type: feature
    - effects:
        - effect: At the start of an encounter, the null chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the null and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 10
intuition: 5
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-null
    source: mcdm.monsters.v1
might: 3
name: Rival Null
organization: Elite
presence: 0
reason: 4
role: Harrier
size: 1M
speed: 7
stability: 3
stamina: "240"
type: statblock
```
