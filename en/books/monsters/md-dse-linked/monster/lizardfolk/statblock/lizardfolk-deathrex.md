---
agility: 2
ev: "12"
file_basename: lizardfolk-deathrex
file_dpath: monster/lizardfolk/statblock
free_strike: 4
intuition: 1
item_id: lizardfolk-deathrex
item_name: Lizardfolk Deathrex
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 3
movement: Climb, swim
name: Lizardfolk Deathrex
organization: Leader
presence: 2
reason: 0
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-deathrex
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "80"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage; [pull](../../../movement/forced-movement.md) 1; A < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 10 damage; [pull](../../../movement/forced-movement.md) 1; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 12 damage; [pull](../../../movement/forced-movement.md) 2; A < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Ripper Spear
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; M < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 12 damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 15 damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Death Roll
      target: One grabbed creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The deathrex moves up to their speed. They can make a [free strike](../../../feature/common/main-actions/free-strike.md) against each creature who makes an opportunity attack against them during this movement.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Trundle
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature or object within distance moves or [shifts](../../../movement/shifting.md) away from the deathrex.
            **Effect:** The deathrex [slides](../../../movement/forced-movement.md) the target up to 5 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Swat the Fly
      target: The triggering creature or object
      type: feature
      usage: Triggered action
    - effects:
        - effect: While the deathrex has a tail, whenever they are affected by an effect that can be ended by a [saving throw](../../../rule/general/saving-throw.md) or that ends at the end of their turn, they can lose their tail to immediately end that effect, then [shift](../../../movement/shifting.md) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Rex Reptilian Escape
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target moves up to their speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). Each target gains temporary [Stamina](../../../rule/health/stamina.md) equal to the damage they deal.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Snack Attack
      target: Self and each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** The deathrex [shifts](../../../movement/shifting.md) up to their speed, leaving behind a shed skin duplicate in the space they started in. The duplicate acts on the deathrex''s turn and has the deathrex''s characteristics, but has 10 [Stamina](../../../rule/health/stamina.md) and no [villain actions](../../../rule/monster/villain-action.md).'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Shed Some Skin
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target moves up to their speed. Until the end of the encounter, whenever a creature comes [adjacent](../../../rule/combat/adjacent.md) to a target or starts their turn there, the target can make a [free strike](../../../feature/common/main-actions/free-strike.md) against them.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Thresher Thrasher
      target: Self and each ally in the area
      type: feature
      usage: '-'
free_strike: 4
intuition: 1
keywords:
    - Humanoid
    - Lizardfolk
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-deathrex
    source: mcdm.monsters.v1
might: 3
movement: Climb, swim
name: Lizardfolk Deathrex
organization: Leader
presence: 2
reason: 0
role: ""
size: "2"
speed: 5
stability: 2
stamina: "80"
type: statblock
```
