---
agility: 3
ev: "144"
file_basename: lich
file_dpath: monster/lich/statblock
free_strike: 10
immunities:
    - Corruption 10
    - poison 10
intuition: 5
item_id: lich
item_name: Lich
keywords:
    - Undead
level: 10
might: 2
movement: Fly, hover
name: Lich
organization: Solo
presence: 5
reason: 5
scc: mcdm.monsters.v1/monster.lich.statblock/lich
size: 1M
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: "650"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 3
ev: "144"
features:
    - effects:
        - effect: At the end of each of their turns, the lich can take 20 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
          name: End Effect
        - effect: The lich can take two turns each round. They can't take turns consecutively.
          name: Solo Turns
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - ability_type: Signature Ability
      distance: Ranged 20
      effects:
        - roll: Power Roll + 5
          tier1: 15 fire damage; A < 4 the target is immolated (save ends)
          tier2: 21 fire damage; A < 5 the target is immolated (save ends)
          tier3: 25 fire damage; A < 6 the target is immolated (save ends)
        - effect: An immolated creature takes 10 fire damage whenever they use a main action and a maneuver on their turn. This damage can't be reduced in any way.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Conflagration
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 10 burst
      effects:
        - roll: Power Roll + 5
          tier1: 8 corruption damage; P < 4 the target is hopeless (save ends)
          tier2: 13 corruption damage; P < 5 the target is hopeless (save ends)
          tier3: 16 corruption damage; P < 6 the target is hopeless (save ends)
        - effect: A hopeless creature can't benefit from edges or double edges, can't gain or use [surges](../../../rule/resource/surge.md), and can't gain temporary [Stamina](../../../rule/health/stamina.md).
          name: Effect
        - cost: 3 Malice
          effect: The distance of this ability increases to a 20 burst and its [potency](../../../rule/character/potency.md) increases by 1.
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Hopeless Place
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 20
      effects:
        - roll: Power Roll + 5
          tier1: 17 psychic damage
          tier2: 24 psychic damage
          tier3: 29 psychic damage
        - effect: A target who has M < 4 is wracked with pain (save ends). A creature wracked with pain has a double bane on abilities.
          name: Effect
        - cost: 3 Malice
          effect: The lich chooses one additional target.
        - cost: 2+ Malice
          effect: 'Each creature wracked with pain gains one of the following conditions of the lich''s choice for each 2 Malice spent: [bleeding](../../../condition/bleeding.md), [slowed](../../../condition/slowed.md), or [prone](../../../condition/prone.md) and can''t stand. These conditions end when a creature is no longer wracked with pain.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Pain Unending
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: The lich becomes spectral, moves up to their speed, and becomes corporeal again. While spectral, the lich automatically ends the [grabbed](../../../condition/grabbed.md) or [restrained](../../../condition/restrained.md) conditions, has damage immunity 5, can move through solid matter, and ignores [difficult terrain](../../../movement/difficult-terrain.md). If the lich ends this movement inside solid matter, they are shunted out into the space from which they entered it.
          name: Effect
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Necrotic Form
      target: Self
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: If the target has P < 4, they swap places with the lich to become the new target of the triggering ability.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Baleful Swap
      target: One enemy
      trigger: The lich is targeted using an ability by a creature other than the target.
      type: feature
      usage: Triggered Action
    - effects:
        - effect: In the lich's presence, death's call is stronger. Any [winded](../../../rule/health/winded.md) creature within 5 squares of the lich is [bleeding](../../../condition/bleeding.md) and can't use the Catch Breath maneuver.
      feature_type: trait
      icon: ⭐️
      name: Herald of Oblivion
      type: feature
    - effects:
        - effect: At the start of each round, the lich chooses a creature within 10 squares. If that creature has R < 4, they are [restrained](../../../condition/restrained.md) until the end of the lich's next turn. The lich can't choose the same creature two rounds in a row.
      feature_type: trait
      icon: ⭐️
      name: Glare of Undeath
      type: feature
    - effects:
        - effect: The lich has a soulstone, which has 50 [Stamina](../../../rule/health/stamina.md) and damage immunity all except to sonic damage and holy damage. If the lich is destroyed while their soulstone is intact, their soul retreats into the soulstone. Any creature who has P < 5 and who moves within 5 squares of an inhabited soulstone for the first time in a round or starts their turn there is compelled (save ends). A compelled creature must do everything in their power to move toward and touch the soulstone.
        - effect: A creature who touches an inhabited soulstone makes a **Might test** that takes a bane.
          tier1: The creature is reduced to 0 [Stamina](../../../rule/health/stamina.md) and the lich manifests [adjacent](../../../rule/combat/adjacent.md) to the soulstone with full [Stamina](../../../rule/health/stamina.md).
          tier2: The creature is reduced to 0 [Stamina](../../../rule/health/stamina.md) and the lich manifests [adjacent](../../../rule/combat/adjacent.md) to the soulstone with 300 [Stamina](../../../rule/health/stamina.md).
          tier3: The creature has their [Stamina](../../../rule/health/stamina.md) reduced to their [winded](../../../rule/health/winded.md) value unless it is already lower, and the lich manifests [adjacent](../../../rule/combat/adjacent.md) to the soulstone with 100 [Stamina](../../../rule/health/stamina.md).
      feature_type: ability
      icon: ⭐️
      name: Rejuvenation
      type: feature
    - cost: Villain Action 1
      distance: Two 3 cubes within 10
      effects:
        - effect: Each target makes an Agility test.
          name: Effect
          tier1: 10 corruption damage; [restrained](../../../condition/restrained.md) (save ends)
          tier2: 16 corruption damage; [restrained](../../../condition/restrained.md) (EoT)
          tier3: 20 corruption damage
        - effect: The lich deals an additional 10 corruption damage to each creature [restrained](../../../condition/restrained.md) this way.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
      name: Cages of Wasting
      target: Each creature in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 12 burst
      effects:
        - effect: A target can't use heroic abilities until the start of the lich's next turn.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: My Power Alone
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 6 burst
      effects:
        - roll: Power Roll + 5
          tier1: 8 corruption damage; A < 4 [frightened](../../../condition/frightened.md) (save ends)
          tier2: 13 corruption damage; A < 5 [frightened](../../../condition/frightened.md) (save ends)
          tier3: 16 corruption damage; A < 6 [frightened](../../../condition/frightened.md) (save ends)
        - effect: At the end of each of the lich's turns, they regain 10 [Stamina](../../../rule/health/stamina.md) for each creature [frightened](../../../condition/frightened.md) this way.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Arms of Necrosis
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 10
immunities:
    - Corruption 10
    - poison 10
intuition: 5
keywords:
    - Undead
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.lich.statblock/lich
    source: mcdm.monsters.v1
might: 2
movement: Fly, hover
name: Lich
organization: Solo
presence: 5
reason: 5
role: ""
size: 1M
speed: 10
stability: 1
stamina: "650"
type: statblock
weaknesses:
    - Holy 5
```
