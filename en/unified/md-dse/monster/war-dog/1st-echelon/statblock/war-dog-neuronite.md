---
agility: 1
ev: "3"
file_basename: war-dog-neuronite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 1
immunities:
    - Psychic 2
intuition: 0
item_id: war-dog-neuronite
item_name: War Dog Neuronite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 0
movement: Fly
name: War Dog Neuronite
organization: Horde
presence: 2
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-neuronite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: 1 burst
      effects:
        - roll: Power Roll + 2
          tier1: 1 psychic damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 2 psychic damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 3 psychic damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: Synlirii Grafts
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Posthumous Promotion
      target: One war dog
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: 5 burst
      effects:
        - effect: '**Effect:** The neuronite chooses one ally within 10 squares. Each target is either taunted by the ally, or the ally has damage immunity 3 whenever any target makes a strike against them (the neuronite''s choice). Either effect lasts until the start of the neuronite''s next turn.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: The Voice
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the neuronite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 1
immunities:
    - Psychic 2
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-neuronite
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: War Dog Neuronite
organization: Horde
presence: 2
reason: 0
role: Defender
size: 1M
speed: 5
stability: 0
stamina: "20"
type: statblock
```
