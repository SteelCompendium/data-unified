---
agility: 4
ev: "9"
file_basename: soulraker-praetorian
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 3
intuition: 2
item_id: soulraker-praetorian
item_name: Soulraker Praetorian
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
might: 2
name: Soulraker Praetorian
organization: Horde
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-praetorian
size: 1L
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 4
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 7 poison damage; push 2
          tier2: 10 poison damage; push 2
          tier3: 11 poison damage; push 4; A < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Barbed Stinger
      target: One creature
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature ends the praetorian's [grab](scc.v1:mcdm.heroes.v1/condition/grabbed).
            **Effect:** The praetorian makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target, breaks off part of their stinger in the target, and [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to half their speed. The target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until they remove the stinger fragment as a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver), taking 6 damage in the process.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Stinging Departure
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: While the praetorian is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature who starts their turn with two or more praetorians [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them takes 6 sonic damage.
      feature_type: trait
      icon: ⭐️
      name: Praetorian Buzzing
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Abyssal
    - Demon
    - Soulraker
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/soulraker-praetorian
    source: mcdm.monsters.v1
might: 2
name: Soulraker Praetorian
organization: Horde
presence: 0
reason: 0
role: Harrier
size: 1L
speed: 8
stability: 0
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
```
