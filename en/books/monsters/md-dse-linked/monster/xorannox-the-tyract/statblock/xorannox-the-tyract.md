---
agility: 2
ev: "96"
file_basename: xorannox-the-tyract
file_dpath: monster/xorannox-the-tyract/statblock
free_strike: 7
intuition: 3
item_id: xorannox-the-tyract
item_name: Xorannox the Tyract
keywords:
    - Horror
    - Overmind
level: 6
might: 4
movement: Fly, hover
name: Xorannox the Tyract
organization: Solo
presence: 3
reason: 4
scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/xorannox-the-tyract
size: "3"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "450"
type: statblock
---

```ds-sb
agility: 2
ev: "96"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of his turns, Xorannox can take 10 damage to end one effect on him that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** Xorannox can take two turns each round. He can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: Six unique eyestalks float around Xorannox, acting on his turn at his command until they are reduced to 0 [Stamina](../../../rule/health/stamina.md). On each of Xorannox's turns, he directs one eyestalk to move and use a [signature ability](../../../rule/combat/signature-ability.md).
      feature_type: trait
      icon: "\U0001F300"
      name: Eyes of the Tyract
      type: feature
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage; [slide](../../../movement/forced-movement.md) 2; M < 2 [bleeding](../../../condition/bleeding.md) (EoT)
          tier2: 20 damage; [slide](../../../movement/forced-movement.md) 3; M < 3 [bleeding](../../../condition/bleeding.md) (EoT)
          tier3: 23 damage; vertical [slide](../../../movement/forced-movement.md) 3; M < 4 [bleeding](../../../condition/bleeding.md) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Toothful Thrashing
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 2 burst
      effects:
        - roll: Power Roll + 4
          tier1: Vertical [push](../../../movement/forced-movement.md) 3
          tier2: Vertical [push](../../../movement/forced-movement.md) 5
          tier3: Vertical [push](../../../movement/forced-movement.md) 7
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: Grav Spike
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Xorannox commands all his eyestalks to move up to their speed.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Optical Collusion
      target: Self
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: 5 x 2 line within 1
      effects:
        - effect: '**Effect:** Xorannox ends all ongoing supernatural effects and suppresses supernatural effects from treasures in the area. New supernatural effects can''t be activated in the area until the end of Xorannox''s next turn.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Shutout
      target: Special
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to Xorannox.
            **Effect:** If the target has I < 3 they are [frightened](../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
        - Ranged
      name: Cower!
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: Xorannox can't be made [frightened](../../../condition/frightened.md) or knocked [prone](../../../condition/prone.md), and he can't be flanked.
      feature_type: trait
      icon: ⭐️
      name: Above It All
      type: feature
    - effects:
        - effect: If Xorannox perceives another overmind or a [voiceless talker](../../group/voiceless-talker.md) on the encounter map, he targets that threat one or more times on each of his turns.
      feature_type: trait
      icon: ⭐️
      name: Natural Enemies
      type: feature
    - cost: Villain Action 1
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 11 psychic damage; R < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 17 psychic damage; R < 3 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 20 psychic damage; R < 4 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Disruption Beam
      target: Three creatures
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** Xorannox recreates any destroyed eyestalks, which return in unoccupied spaces on the encounter map with full [Stamina](../../../rule/health/stamina.md).'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: All Eyes, All Rise
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 2 burst
      effects:
        - effect: '**Effect:** Xorannox directs each of his eyestalks to use a [signature ability](../../../rule/combat/signature-ability.md) against any target.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Panoptibeam
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 7
intuition: 3
keywords:
    - Horror
    - Overmind
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.xorannox-the-tyract.statblock/xorannox-the-tyract
    source: mcdm.monsters.v1
might: 4
movement: Fly, hover
name: Xorannox the Tyract
organization: Solo
presence: 3
reason: 4
role: ""
size: "3"
speed: 5
stability: 2
stamina: "450"
type: statblock
```
