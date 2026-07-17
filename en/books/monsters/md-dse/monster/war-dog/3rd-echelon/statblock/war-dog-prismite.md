---
agility: 0
ev: "10"
file_basename: war-dog-prismite
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
intuition: 2
item_id: war-dog-prismite
item_name: War Dog Prismite
keywords:
    - Soulless
    - War Dog
level: 8
might: 4
movement: Fly, hover
name: War Dog Prismite
organization: Horde
presence: 3
reason: 4
role: Defender
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-prismite
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "82"
type: statblock
---

```ds-sb
agility: 0
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 2 burst
      effects:
        - roll: Power Roll + 4
          tier1: 3 psychic damage
          tier2: 6 psychic damage; R < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 8 psychic damage; R < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) and the target takes a bane on the Escape Grab maneuver, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
        - Weapon
      name: Grasping Tonguetacles
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: 4 cube within 10
      effects:
        - effect: '**Effect:** Until the start of the prismite''s next turn, each target has cover and gains a +2 bonus to stability.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
      name: Hard Light Field
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An enemy within distance uses a melee ability against an ally.
            **Effect:** The target is [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 5 squares toward the prismite and any damage from the triggering ability is halved.
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
        - Ranged
      name: Tractor Beam
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: When the prismite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they explode, dealing 3d6 psychic damage to each enemy within 2 squares of them.
      feature_type: trait
      icon: ⭐️
      name: Prismacore Detonation
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Soulless
    - War Dog
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-prismite
    source: mcdm.monsters.v1
might: 4
movement: Fly, hover
name: War Dog Prismite
organization: Horde
presence: 3
reason: 4
role: Defender
size: "2"
speed: 5
stability: 2
stamina: "82"
type: statblock
```
