---
agility: 5
ev: "144"
file_basename: meteor-dragon
file_dpath: monster/dragon/statblock
free_strike: 10
intuition: 3
item_id: meteor-dragon
item_name: Meteor Dragon
keywords:
    - Dragon
    - Elemental
level: 10
might: 5
movement: Fly
name: Meteor Dragon
organization: Solo
presence: 5
reason: 3
scc: mcdm.monsters.v1/monster.dragon.statblock/meteor-dragon
size: "3"
source: mcdm.monsters.v1
speed: 15
stability: 6
stamina: "650"
type: statblock
---

```ds-sb
agility: 5
ev: "144"
features:
    - effects:
        - effect: |-
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the dragon can take 20 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
            **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The dragon's scales create a 1 aura of void space around them. Any enemy who starts their turn in the area takes 10 cold damage and is suffocating. Each time the dragon takes damage, the area of the aura increases by 1 (to a maximum of 5), and they deal an extra 5 damage the next time they use an ability that deals rolled damage.
      feature_type: trait
      icon: ❇️
      name: Voidshroud Wyrmscale Aura
      type: feature
    - ability_type: Signature Ability
      distance: 4 cube within 10
      effects:
        - roll: ""
          tier1: 20 sonic damage; the target is dragonsealed (save ends)
          tier2: 16 sonic damage; the target is dragonsealed (save ends)
          tier3: 10 sonic damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Gravity Well
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - distance: Melee 2 or ranged 15
      effects:
        - roll: Power Roll + 5
          tier1: 15 holy damage; A < 4 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 21 holy damage; A < 5 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 25 holy damage; A < 6 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Cosmic Tail Ray
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, the dragon chooses a target within 3 squares. The dragon can make a [free strike](../../../feature/common/main-actions/free-strike.md) against the target, and ignores [banes](../../../rule/dice/bane.md) when using abilities against the target until the start of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Crescent Claws
      type: feature
    - cost: 5 Malice
      distance: 15 burst
      effects:
        - effect: '**Effect:** Each target must be dragonsealed. The dragon chooses a direction and vertical slides each target 10 squares in that direction, ignoring [stability](../../../rule/character/stability.md). A target who strikes an obstacle takes damage as if they had fallen the [forced movement](../../../movement/forced-movement.md) distance.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Investiture of Gravity
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The dragon takes damage from an ability while the area of their Voidshroud Wyrmscale Aura is 2 or more.
            **Effect:** The dragon halves the damage. Each enemy and object in the area of the dragon's Voidshroud Wyrmscale Aura trait takes 5 sonic damage and is pulled up to 5 squares toward the dragon. The area of the wyrmscale aura then resets to 1.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Field Collapse
      target: Self
      type: feature
      usage: Free triggered action
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - roll: Power Roll + 5
          tier1: 10 psychic damage; P < 4 [frightened](../../../condition/frightened.md) (save ends)
          tier2: 16 psychic damage; P < 5 [frightened](../../../condition/frightened.md) (save ends)
          tier3: 20 psychic damage; P < 6 [frightened](../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: A Hero Faces the Void
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - cost: Villain Action 1
      distance: 1-mile burst
      effects:
        - effect: |-
            **Effect:** Each target takes 30 fire damage, and if they have M < 5, they are knocked [prone](../../../condition/prone.md).
            **Special:** The dragon can use this ability before the encounter begins.
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Impactful Arrival
      target: Each creature and object in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** Until the end of the encounter, each enemy who is dragonsealed and [weakened](../../../condition/weakened.md) and who the dragon has [line of effect](../../../rule/combat/line-of-effect.md) to loses 1 of their Heroic Resource at the start of each of their turns (to a minimum of 0). The dragon then uses their Cosmic Tail Ray ability with a double [edge](../../../rule/dice/edge.md), targeting four creatures or objects.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Burning Aurora
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: ∞ x 3 line within 1
      effects:
        - roll: ""
          tier1: 25 damage; I < 6 the target is annihilated
          tier2: 21 damage; I < 5 the target is annihilated
          tier3: 15 damage; I < 4 the target is annihilated
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Voidlight Breath
      target: Each enemy and object in the area
      type: feature
      usage: '-'
free_strike: 10
intuition: 3
keywords:
    - Dragon
    - Elemental
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.dragon.statblock/meteor-dragon
    source: mcdm.monsters.v1
might: 5
movement: Fly
name: Meteor Dragon
organization: Solo
presence: 5
reason: 3
role: ""
size: "3"
speed: 15
stability: 6
stamina: "650"
type: statblock
```
