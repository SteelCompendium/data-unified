---
agility: 2
ev: "20"
file_basename: orc-warleader
file_dpath: monster/orc/statblock
free_strike: 5
intuition: 2
item_id: orc-warleader
item_name: Orc Warleader
keywords:
    - Humanoid
    - Orc
level: 3
might: 3
name: Orc Warleader
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.orc.statblock/orc-warleader
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - effect: |-
            **Effect:** The target moves up to their speed and can use a main action.
            **1 [Malice](../../../rule/monster/malice.md):** The warleader targets two allies.
            **3 [Malice](../../../rule/monster/malice.md):** The warleader targets one ally and a [minion](../../../rule/organization/minion.md) [squad](../../../rule/monster/squad.md).
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Go.
      target: One ally
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage; [push](../../../movement/forced-movement.md) 1; M < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 10 damage; [push](../../../movement/forced-movement.md) 3; M < 2 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 13 damage; [push](../../../movement/forced-movement.md) 5; M < 3 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Mace Lariat
      target: Each enemy
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Self and ranged 10
      effects:
        - effect: '**Effect:** Each target moves up to their speed and can use the [Grab](../../../feature/common/maneuvers/grab.md) maneuver, which gains an edge.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Lockdown
      target: Self and three allies
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** The target obtains a tier 1 outcome on one power roll.
            **Effect:** The target has a double edge on their next power roll before the end of the encounter.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Courtesy Call
      target: One creature
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - roll: ""
          tier1: '[Frightened](../../../condition/frightened.md) of the warleader (save ends)'
          tier2: '[Frightened](../../../condition/frightened.md) of the warleader (EoT)'
          tier3: No effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Close In
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The warleader [shifts](../../../movement/shifting.md) up to their speed, and four orc blitzers appear in unoccupied spaces within distance.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: Familial Reinforcements
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Self
      effects:
        - effect: '**Effect:** Three times in succession, the warleader [shifts](../../../movement/shifting.md) up to their speed and can use Mace Lariat.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: I'll Do This Myself
      target: Self
      type: feature
      usage: '-'
    - effects:
        - effect: At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: If the warleader is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the warleader is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Orc
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-warleader
    source: mcdm.monsters.v1
might: 3
name: Orc Warleader
organization: Leader
presence: 2
reason: 1
role: ""
size: 1M
speed: 6
stability: 2
stamina: "120"
type: statblock
```
