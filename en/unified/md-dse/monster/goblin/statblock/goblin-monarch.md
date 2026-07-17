---
agility: 3
ev: "12"
file_basename: goblin-monarch
file_dpath: monster/goblin/statblock
free_strike: 4
intuition: 0
item_id: goblin-monarch
item_name: Goblin Monarch
keywords:
    - Goblin
    - Humanoid
level: 1
might: 0
movement: Climb
name: Goblin Monarch
organization: Leader
presence: 3
reason: 1
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-monarch
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 1
stamina: "80"
type: statblock
---

```ds-sb
agility: 3
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage
          tier2: 10 damage
          tier3: 13 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Handaxe
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Ranged 20
      effects:
        - effect: '**Effect:** Two goblin runners appear in unoccupied spaces within distance.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Get in Here!
      target: Special
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature targets the monarch with a strike.
            **Effect:** The ally is the target of the triggering strike instead.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Meat Shield
      target: One ally
      type: feature
      usage: Triggered action
    - effects:
        - effect: The monarch doesn't provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
    - effects:
        - effect: At the end of each of their turns, the monarch can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target can move up to their speed or make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: What Are You Waiting For?
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each ally within 10 squares of the target can move up to their speed toward the target.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: Focus Fire
      target: One enemy or object
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Special
      effects:
        - effect: '**Effect:** Each enemy in the encounter takes 2 damage for each goblin [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Kill!
      target: Special
      type: feature
      usage: '-'
free_strike: 4
intuition: 0
keywords:
    - Goblin
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-monarch
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Goblin Monarch
organization: Leader
presence: 3
reason: 1
role: ""
size: 1S
speed: 6
stability: 1
stamina: "80"
type: statblock
```
