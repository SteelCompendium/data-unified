---
agility: -1
ev: "96"
file_basename: olothec
file_dpath: monster/olothec/statblock
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
item_id: olothec
item_name: Olothec
keywords:
    - Horror
    - Olothec
level: 6
might: 4
movement: Fly, swim
name: Olothec
organization: Solo
presence: 3
reason: 4
scc: mcdm.monsters.v1/monster.olothec.statblock/olothec
size: "2"
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "450"
type: statblock
---

```ds-sb
agility: -1
ev: "96"
features:
    - effects:
        - effect: |-
            [**End Effect:**](../../../rule/monster/end-effect.md) At the end of each of their turns, the olothec can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** The olothec can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: A creature permanently devolves into a slime servant if they spend 1 continuous minute [weakened](../../../condition/weakened.md) by Devolving Tentacles, they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by the psychic damage from Devolving Tentacles, or they suffer all three transformations from Oozing Transformation.
      feature_type: trait
      icon: ⭐️
      name: Gelatinosis
      type: feature
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; M < 2 [weakened](../../../condition/weakened.md) or the target is slimed (save ends)
          tier2: 17 damage; M < 3 [weakened](../../../condition/weakened.md) or the target is slimed (save ends)
          tier3: 20 damage; M < 4 [weakened](../../../condition/weakened.md) and the target is slimed (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Devolving Tentacles
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 7 x 2 line within 1
      effects:
        - roll: Power Roll + 4
          tier1: 6 acid damage; A < 2 [push](../../../movement/forced-movement.md) special
          tier2: 10 acid damage; A < 3 [push](../../../movement/forced-movement.md) special
          tier3: 13 acid damage; A < 4 [push](../../../movement/forced-movement.md) special and [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Slime Spew
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 13 psychic damage; I < 2 the target is transformed (save ends)
          tier2: 20 psychic damage; I < 3 the target is transformed (save ends)
          tier3: 23 psychic damage; I < 4 the target is transformed (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Oozing Transformation
      target: One creature
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The olothec [teleports](../../../movement/teleport.md) to an unoccupied space within 10 squares. Alternatively, they swap places with a creature or object within 5 squares of them.'
      feature_type: ability
      icon: "\U0001F464"
      keywords:
        - Psionic
      name: Jaunt
      target: Self
      type: feature
      usage: Maneuver
    - distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** An enemy within distance deals damage to the olothec.
            **Effect:** The target takes 8 psychic damage and has psychic weakness 3 until the end of the olothec's next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
        - Ranged
      name: Liquify
      target: Each enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: The olothec can't be made [frightened](../../../condition/frightened.md) or [taunted](../../../condition/taunted.md).
      feature_type: trait
      icon: ⭐️
      name: Primordial Mind
      type: feature
    - effects:
        - effect: A slimed or transformed creature can't have concealment from or be hidden from the olothec.
      feature_type: trait
      icon: ⭐️
      name: Slime Sense
      type: feature
    - cost: Villain Action 1
      distance: Ranged 20
      effects:
        - roll: Power Roll + 4
          tier1: 10 psychic damage; P < 2 [frightened](../../../condition/frightened.md) (save ends)
          tier2: 14 psychic damage; P < 3 [frightened](../../../condition/frightened.md) (save ends)
          tier3: 17 psychic damage; P < 4 [frightened](../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Horrifying Form
      target: Each enemy
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 10 burst
      effects:
        - effect: '**Effect:** The olothec [slides](../../../movement/forced-movement.md) each target up to 5 squares. Each target takes 12 psychic damage, and if they have M < 3 they are [weakened](../../../condition/weakened.md) and slimed (save ends). A slimed target takes 4 psychic damage whenever they make a power roll. Additionally, until the start of their next turn, the olothec has damage immunity 4.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Psionic
      name: Psychic Pulse
      target: Each creature in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 10 burst
      effects:
        - roll: Power Roll + 4
          tier1: 7 psychic damage; R < 2 the target is devolved (save ends)
          tier2: 13 psychic damage; R < 3 the target is devolved (save ends)
          tier3: 16 psychic damage; R < 3 the target is devolved (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Psionic
      name: Return to Perfection
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Horror
    - Olothec
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.olothec.statblock/olothec
    source: mcdm.monsters.v1
might: 4
movement: Fly, swim
name: Olothec
organization: Solo
presence: 3
reason: 4
role: ""
size: "2"
speed: 7
stability: 0
stamina: "450"
type: statblock
```
