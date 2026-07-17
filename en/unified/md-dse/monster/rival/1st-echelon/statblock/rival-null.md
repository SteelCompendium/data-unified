---
agility: 2
ev: "16"
file_basename: rival-null
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 2
item_id: rival-null
item_name: Rival Null
keywords:
    - Humanoid
    - Rival
level: 2
might: 0
name: Rival Null
organization: Elite
presence: 0
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-null
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "80"
type: statblock
---

```ds-sb
agility: 2
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
          tier2: 10 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
          tier3: 13 damage; the null [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Nimble Step
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; R < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
          tier2: 10 damage; R < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
          tier3: 13 damage; R < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Numb
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time each round that the null is targeted by a damage-dealing [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they halve the damage.
      feature_type: trait
      icon: ⭐️
      name: Inertial Shield
      type: feature
    - effects:
        - effect: At the start of an encounter, the null chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the null and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-null
    source: mcdm.monsters.v1
might: 0
name: Rival Null
organization: Elite
presence: 0
reason: 1
role: Harrier
size: 1M
speed: 7
stability: 3
stamina: "80"
type: statblock
```
