---
agility: 1
ev: "36"
file_basename: arixx
file_dpath: monster/arixx/statblock
free_strike: 5
intuition: 1
item_id: arixx
item_name: Arixx
keywords:
    - Arixx
    - Beast
level: 1
might: 3
movement: Burrow
name: Arixx
organization: Solo
presence: -4
reason: -3
scc: mcdm.monsters.v1/monster.arixx.statblock/arixx
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "200"
type: statblock
---

```ds-sb
agility: 1
ev: "36"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the arixx can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** The arixx can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: '[Difficult terrain](../../../movement/difficult-terrain.md) composed of earth or loose rock doesn''t cost the arixx extra movement.'
      feature_type: trait
      icon: ⭐️
      name: Earthwalk
      type: feature
    - effects:
        - effect: A [prone](../../../condition/prone.md) creature making a melee strike against the arixx has a double [edge](../../../rule/dice/edge.md) on the strike instead of taking a [bane](../../../rule/dice/bane.md).
      feature_type: trait
      icon: ⭐️
      name: Soft Underbelly
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; [grabbed](../../../condition/grabbed.md)
          tier2: 13 damage; [grabbed](../../../condition/grabbed.md)
          tier3: 16 damage; [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Bite
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage; A < 1 [grabbed](../../../condition/grabbed.md)
          tier2: 8 damage; A < 2 [grabbed](../../../condition/grabbed.md)
          tier3: 11 damage; A < 3 [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Claw Swing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 4 acid damage
          tier2: 6 acid damage
          tier3: 7 acid damage; [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Spitfire
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 3
          tier1: 4 damage
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 2
          tier3: 7 damage; [push](../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Dirt Devil
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: 1 burst
      effects:
        - effect: '**Effect:** The arixx kicks up dust to fill the area until the start of their next turn, then moves up to their speed. Any enemy in the area or who targets a creature in the area takes a [bane](../../../rule/dice/bane.md) on power rolls.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Dust Cloud
      target: Special
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The arixx takes damage.
            **Effect:** The arixx halves the damage and [shifts](../../../movement/shifting.md) up to 3 squares after the triggering effect resolves.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Skitter
      target: Self
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: 10 x 2 line within 1
      effects:
        - roll: Power Roll + 3
          tier1: 5 acid damage
          tier2: 8 acid damage
          tier3: 11 acid damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: Acid Spew
      target: Each creature and object in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** The arixx [shifts](../../../movement/shifting.md) up to their speed. If they end this shift above ground and within 2 squares of a creature, they use Bite against the creature and can then use the Dig maneuver.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Sinkhole
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 2 burst
      effects:
        - roll: Power Roll + 3
          tier1: 5 acid damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 8 acid damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 11 acid damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: Acid and Claws
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 1
keywords:
    - Arixx
    - Beast
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.arixx.statblock/arixx
    source: mcdm.monsters.v1
might: 3
movement: Burrow
name: Arixx
organization: Solo
presence: -4
reason: -3
role: ""
size: "2"
speed: 5
stability: 2
stamina: "200"
type: statblock
```
