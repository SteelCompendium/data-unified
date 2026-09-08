---
agility: 1
ev: "28"
file_basename: devil-legate
file_dpath: monster/devil/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 1
item_id: devil-legate
item_name: Devil Legate
keywords:
    - Devil
    - Infernal
level: 5
might: 3
name: Devil Legate
organization: Elite
presence: 2
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.devil.statblock/devil-legate
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "160"
type: statblock
---

```ds-sb
agility: 1
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 14 damage; A < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 17 damage; A < 3 [slowed](../../../condition/slowed.md) (save ends)
        - effect: If the targets are [adjacent](../../../rule/combat/adjacent.md) to each other, this ability deals an extra 3 damage.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Infernal Pike
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 6 damage; M < 1 [prone](../../../condition/prone.md)
          tier2: 11 damage; M < 2 [prone](../../../condition/prone.md) and can't stand (save ends)
          tier3: 14 damage; M < 3 [prone](../../../condition/prone.md) and can't stand (save ends)
        - effect: If this ability is used as part of the [Charge](../../../feature/common/main-actions/charge.md) main action, the legate ignores [difficult terrain](../../../movement/difficult-terrain.md) during the charge. Each creature and object whose space the legate moves through takes the damage from this ability, but not its additional effects.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Writ of Execution
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: The target is [taunted](../../../condition/taunted.md) by the legate (save ends). The legate can have only one creature [taunted](../../../condition/taunted.md) at a time.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Law and Order
      target: One creature
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - effect: The target makes a Presence test.
          name: Effect
          tier1: The legate chooses a new target for the strike.
          tier2: The legate halves the triggering damage.
          tier3: The target takes a [bane](../../../rule/dice/bane.md) on the strike.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Devilish Charm
      target: The triggering creature
      trigger: A creature targets the legate with a strike.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The legate has damage immunity 3 while in one of the Seven Cities of Hell or within 10 squares of a non-[minion](../../../rule/organization/minion.md) devil who is of a higher level than them.
      feature_type: trait
      icon: ⭐️
      name: Hellish Bailiff
      type: feature
    - effects:
        - effect: If a creature within 10 squares speaks the legate's true name, the legate loses their damage immunities, any nondamaging effects of their [signature ability](../../../rule/combat/signature-ability.md), and their Devilish Charm ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 6
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.devil.statblock/devil-legate
    source: mcdm.monsters.v1
might: 3
name: Devil Legate
organization: Elite
presence: 2
reason: 0
role: Defender
size: 1M
speed: 6
stability: 2
stamina: "160"
type: statblock
```
