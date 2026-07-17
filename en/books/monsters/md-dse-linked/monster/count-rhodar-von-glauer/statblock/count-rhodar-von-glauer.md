---
agility: 5
ev: "144"
file_basename: count-rhodar-von-glauer
file_dpath: monster/count-rhodar-von-glauer/statblock
free_strike: 10
immunities:
    - Corruption 10
    - poison 10
intuition: 2
item_id: count-rhodar-von-glauer
item_name: Count Rhodar von Glauer
keywords:
    - Undead
    - Vampire
level: 10
might: 3
movement: Fly, hover, teleport
name: Count Rhodar von Glauer
organization: Solo
presence: 3
reason: 2
scc: mcdm.monsters.v1/monster.count-rhodar-von-glauer.statblock/count-rhodar-von-glauer
size: 1M
source: mcdm.monsters.v1
speed: 12
stability: 3
stamina: "650"
type: statblock
---

```ds-sb
agility: 5
ev: "144"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of his turns, Rhodar can take 20 damage to end one effect on him that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** Rhodar can take two turns each round. He can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: Rhodar has damage immunity 5. If he takes holy damage, he loses this immunity until the end of the round.
      feature_type: trait
      icon: ⭐️
      name: Grave Ward
      type: feature
    - effects:
        - effect: Each enemy within 10 squares of Rhodar takes a -2 penalty to [saving throws](../../../rule/general/saving-throw.md).
      feature_type: trait
      icon: ⭐️
      name: Thin the Blood
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2 or ranged 15
      effects:
        - roll: Power Roll + 5
          tier1: 13 damage; A < 4 [restrained](../../../condition/restrained.md) (save ends)
          tier2: 18 damage; A < 5 [restrained](../../../condition/restrained.md) (save ends)
          tier3: 21 damage; A < 6 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Spear of the Damned
      target: Three creatures or objects
      type: feature
      usage: Main action
    - distance: 5 burst
      effects:
        - roll: ""
          tier1: 16 corruption damage; [frightened](../../../condition/frightened.md) (save ends)
          tier2: 13 corruption damage; [frightened](../../../condition/frightened.md) (EoT)
          tier3: 8 corruption damage
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Disarming Glare
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 17 corruption damage; M < 4 [bleeding](../../../condition/bleeding.md) (save ends) and [prone](../../../condition/prone.md)
          tier2: 24 corruption damage; [prone](../../../condition/prone.md); M < 5 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 30 corruption damage; [prone](../../../condition/prone.md); M < 6 the target is [bleeding](../../../condition/bleeding.md) until the end of the encounter
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
        - Strike
      name: Vermilion Fangs
      target: One creature
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 2 burst
      effects:
        - roll: Power Roll + 5
          tier1: 6 damage, 2 corruption damage; [push](../../../movement/forced-movement.md) 2; M < 4 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 6 damage, 7 corruption damage; [push](../../../movement/forced-movement.md) 5; M < 5 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 6 damage, 10 corruption damage; [push](../../../movement/forced-movement.md) 7; M < 6 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Sanguineous Flourish
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Two 3 cubes within 5
      effects:
        - effect: '**Effect:** Each area is saturated with vengeful spirits until the end of the round. Any enemy who enters the area for the first time in a round or starts their turn there takes 5 corruption damage. At the end of the round, the spirits violently disperse. Each enemy within 2 squares of an area and has P < 5 is [weakened](../../../condition/weakened.md) (save ends).'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Vengeance of Rhöl
      target: Special
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature within distance makes a strike against Rhodar.
            **Effect:** A target who has I < 5 is [frightened](../../../condition/frightened.md). This effect ends if the target is 11 or more squares from Rhodar.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Reactive Rebuke
      target: The triggering creature
      type: feature
      usage: Triggered Action
    - effects:
        - effect: Rhodar has speed 15 and an edge on power rolls while any creature within 20 squares of him is [bleeding](../../../condition/bleeding.md). Any [bleeding](../../../condition/bleeding.md) creature within 10 squares of Rhodar can't hide.
      feature_type: trait
      icon: ⭐️
      name: Lord's Bloodthirst
      type: feature
    - cost: Villain Action 1
      distance: 8 cube within 15
      effects:
        - roll: Power Roll + 5
          tier1: 8 corruption damage; A < 4 the target is blood soaked (save ends)
          tier2: 13 corruption damage; A < 5 the target is blood soaked (save ends)
          tier3: 16 corruption damage; A < 6 the target is blood soaked until the end of the encounter
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
      name: Red Tide
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - roll: ""
          tier1: 16 corruption damage; the target is [bleeding](../../../condition/bleeding.md) until the end of the encounter
          tier2: 13 corruption damage; [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 8 corruption damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Sanguine Mist
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 15 x 3 line within 1
      effects:
        - roll: Power Roll + 5
          tier1: 10 fire damage; R < 4 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 16 fire damage; R < 5 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 20 fire damage; R < 6 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Fires of Dracul
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 10
immunities:
    - Corruption 10
    - poison 10
intuition: 2
keywords:
    - Undead
    - Vampire
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.count-rhodar-von-glauer.statblock/count-rhodar-von-glauer
    source: mcdm.monsters.v1
might: 3
movement: Fly, hover, teleport
name: Count Rhodar von Glauer
organization: Solo
presence: 3
reason: 2
role: ""
size: 1M
speed: 12
stability: 3
stamina: "650"
type: statblock
```
