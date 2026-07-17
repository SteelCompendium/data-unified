---
agility: 1
ev: "8"
file_basename: orc-terranova
file_dpath: monster/orc/statblock
free_strike: 4
intuition: 1
item_id: orc-terranova
item_name: Orc Terranova
keywords:
    - Humanoid
    - Orc
level: 2
might: 1
movement: Burrow
name: Orc Terranova
organization: Platoon
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.orc.statblock/orc-terranova
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "30"
type: statblock
---

```ds-sb
agility: 1
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; A < 0 [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (save ends)
          tier2: 9 damage; A < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (save ends)
          tier3: 12 damage; A < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Earth Pillar
      target: Three creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage; M < 0 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 7 damage; M < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 10 damage; M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Sinkhole
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The terranova ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Additionally, they don't need [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) to use abilities against creatures touching the ground.
      feature_type: trait
      icon: ⭐️
      name: Seismic Step
      type: feature
    - effects:
        - effect: If the terranova is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying. If the target of the free strike is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the terranova is reduced to 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Humanoid
    - Orc
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-terranova
    source: mcdm.monsters.v1
might: 1
movement: Burrow
name: Orc Terranova
organization: Platoon
presence: 2
reason: 0
role: Controller
size: 1M
speed: 6
stability: 2
stamina: "30"
type: statblock
```
