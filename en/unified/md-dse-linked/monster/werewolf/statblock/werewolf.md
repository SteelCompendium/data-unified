---
agility: 2
ev: "36"
file_basename: werewolf
file_dpath: monster/werewolf/statblock
free_strike: 5
intuition: 1
item_id: werewolf
item_name: Werewolf
keywords:
    - Accursed
    - Humanoid
    - Werebeast
level: 1
might: 3
name: Werewolf
organization: Solo
presence: 1
reason: -1
scc: mcdm.monsters.v1/monster.werewolf.statblock/werewolf
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "200"
type: statblock
---

```ds-sb
agility: 2
ev: "36"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the werewolf can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
            **Solo Turns:** The werewolf can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The werewolf's ferocity is expressed through rage, and their abilities can inflict rage points on any enemy except a stormwight [fury](../../../class/fury.md). A creature who starts their turn with 10 or more rage expends their rage. Then before taking their turn, they must [shift](../../../movement/shifting.md) up to their speed toward the nearest creature and make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against them. A creature who takes damage from this [free strike](../../../feature/common/main-actions/free-strike.md) gains 1 rage. Accumulated rage disappears after a character finishes a respite.
      feature_type: trait
      icon: ⭐️
      name: Accursed Rage
      type: feature
    - effects:
        - effect: The werewolf enters combat in their hybrid humanoid form. Their shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Shapeshifter
      type: feature
    - effects:
        - effect: The werewolf ignores [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Vukenstep
      type: feature
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; the target gains 2 rage
          tier2: 13 damage; the target gains 4 rage
          tier3: 16 damage; the target gains 5 rage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Accursed Bite
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 11 damage; the target gains 1 rage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 14 damage; the target gains 3 rage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Ripping Claws
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 1 burst
      effects:
        - roll: Power Roll + 3
          tier1: 4 damage; [push](../../../movement/forced-movement.md) 2
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 3; the target gains 1 rage
          tier3: 7 damage; [slide](../../../movement/forced-movement.md) 3; the target gains 3 rage
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Berserker Slash
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The werewolf jumps up to 4 squares. If they end this jump at a wall, the werewolf jumps off the wall up to 4 squares and can make a melee [free strike](../../../feature/common/main-actions/free-strike.md). If the target of the [free strike](../../../feature/common/main-actions/free-strike.md) has M < 2, they are knocked [prone](../../../condition/prone.md).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Wall Leap
      target: Self
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature within distance targets the werewolf with a melee ability after charging or moving 2 or more squares in a straight line toward them.
            **Effect:** The target is knocked [prone](../../../condition/prone.md) and takes 5 damage before the [triggered action](../../../rule/combat/triggered-action.md) is resolved.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Facepalm and Head Slam
      target: The triggering creature
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - roll: ""
          tier1: The target must move their speed in a straight line away from the werewolf; [frightened](../../../condition/frightened.md) (save ends)
          tier2: '[Frightened](../../../condition/frightened.md) (EoT)'
          tier3: No effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Howl
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** The werewolf transforms into a massive wolf of size 3 until they die or until the end of the encounter. They move to a space that can accommodate their new size and [push](../../../movement/forced-movement.md) [adjacent](../../../rule/combat/adjacent.md) creatures out of their way. While in wolf form, they have speed 10 and stability 2, their strikes gain a +2 damage bonus and bestow an additional 1 rage, and the [potency](../../../rule/character/potency.md) of Accursed Bite increases by 1.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Full Wolf
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 2 burst
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage; the target gains 2 rage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 8 damage; the target gains 4 rage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 11 damage; the target gains 8 rage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Weapon
      name: Rampage
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 1
keywords:
    - Accursed
    - Humanoid
    - Werebeast
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.werewolf.statblock/werewolf
    source: mcdm.monsters.v1
might: 3
name: Werewolf
organization: Solo
presence: 1
reason: -1
role: ""
size: 1M
speed: 7
stability: 0
stamina: "200"
type: statblock
```
