---
agility: -2
ev: "48"
file_basename: servok-war-engine
file_dpath: monster/valok/statblock
free_strike: 10
intuition: -1
item_id: servok-war-engine
item_name: Servok War Engine
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 10
might: 5
name: Servok War Engine
organization: Elite
presence: -5
reason: -4
role: Brute
scc: mcdm.monsters.v1/monster.valok.statblock/servok-war-engine
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 8
stamina: "260"
type: statblock
---

```ds-sb
agility: -2
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage
          tier2: 21 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 25 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Blade Rake
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 20
      effects:
        - roll: Power Roll + 5
          tier1: 22 damage
          tier2: 29 damage; I < 4 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 34 damage; I < 5 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Prismacore Cannon
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The war engine moves up to their speed in a straight line, automatically destroying mundane size 1 objects or walls in their path. The first time the war engine moves through a creature''s space during this movement, that creature can choose to either fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or take 10 damage.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Destructive Rollout
      target: Self
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: 20 x 1 line within 1
      effects:
        - roll: ""
          tier1: 16 fire damage; the target is burning (save ends)
          tier2: 12 fire damage; the target is burning (EoT)
          tier3: 8 fire damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Burning Oil
      target: Each enemy and object in the area
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Ranged 20
      effects:
        - roll: Power Roll + 5
          tier1: 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 12 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Quick Blast
      target: One creature or object
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The war engine ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), and their abilities deal an extra 15 damage to objects.
      feature_type: trait
      icon: ⭐️
      name: Servok Siege Machine
      type: feature
    - effects:
        - effect: The war engine's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Crafted to Perfection
      type: feature
    - effects:
        - effect: While the war engine isn't [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), or [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
      feature_type: trait
      icon: ⭐️
      name: Valiar Might
      type: feature
free_strike: 10
intuition: -1
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.valok.statblock/servok-war-engine
    source: mcdm.monsters.v1
might: 5
name: Servok War Engine
organization: Elite
presence: -5
reason: -4
role: Brute
size: "3"
speed: 5
stability: 8
stamina: "260"
type: statblock
```
