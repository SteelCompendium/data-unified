---
agility: 4
ev: "84"
file_basename: medusa
file_dpath: monster/medusa/statblock
free_strike: 8
intuition: 0
item_id: medusa
item_name: Medusa
keywords:
    - Accursed
    - Humanoid
    - Medusa
level: 5
might: 2
name: Medusa
organization: Solo
presence: 0
reason: 0
scc: mcdm.monsters.v1/monster.medusa.statblock/medusa
size: 1M
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: "420"
type: statblock
---

```ds-sb
agility: 4
ev: "84"
features:
    - effects:
        - effect: '[**End Effect:**](../../../rule/monster/end-effect.md) At the end of each of their turns, the medusa can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can''t be reduced in any way.'
        - effect: The medusa can take two turns each round. They can't take turns consecutively.
          name: Solo Turns
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 16 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 19 damage; M < 4 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Snake Bites
      target: Two creatures or objects
      type: feature
      usage: Main action
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 11 damage; [push](../../../movement/forced-movement.md) 3
          tier2: 16 damage; [push](../../../movement/forced-movement.md) 5
          tier3: 19 damage; [push](../../../movement/forced-movement.md) 7
        - cost: 3 Malice
          effect: The medusa targets two additional creatures or objects.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Damning Gaze
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 4
          tier1: M < 2 [restrained](../../../condition/restrained.md) (save ends)
          tier2: M < 3 [restrained](../../../condition/restrained.md) (save ends)
          tier3: '[Slowed](../../../condition/slowed.md) (save ends); or if M < 4 [restrained](../../../condition/restrained.md) (save ends)'
        - effect: A target with cover reduces the [potency](../../../rule/character/potency.md) by 1, while a [slowed](../../../condition/slowed.md) target increases the [potency](../../../rule/character/potency.md) by 1. A target [restrained](../../../condition/restrained.md) this way magically begins to turn to stone, and a target who ends two consecutive turns [restrained](../../../condition/restrained.md) this way is petrified.
          name: Effect
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Petrify
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: The medusa [shifts](../../../movement/shifting.md) up to 3 squares and can attempt to hide even if observed.
          name: Effect
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Nimble Escape
      target: Self
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 13 acid damage
          tier2: 18 acid damage
          tier3: 22 acid damage
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Venomous Spit
      target: The triggering creature
      trigger: A creature within distance deals damage to the medusa.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The medusa gains an edge on power rolls against any creature who is [restrained](../../../condition/restrained.md) or [slowed](../../../condition/slowed.md) by Petrify.
      feature_type: trait
      icon: ⭐️
      name: Cunning Edge
      type: feature
    - effects:
        - effect: The medusa can't be flanked.
      feature_type: trait
      icon: ⭐️
      name: Many Peering Eyes
      type: feature
    - cost: Villain Action 1
      distance: Ranged 50
      effects:
        - effect: The medusa can use Petrify against each target without spending [Malice](../../../rule/monster/malice.md). A target who doesn't have cover increases the [potency](../../../rule/character/potency.md) by 1.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
        - Ranged
      name: Mass Petrify
      target: Each enemy
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: The medusa temporarily manifests wings and [flies](../../../movement/fly.md) up to their speed without provoking opportunity attacks. During or after this movement, they can use Snake Bites and Damning Gaze once each.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Serpent Wings
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 10 burst
      effects:
        - roll: Power Roll + 4
          tier1: 8 acid damage; P < 3 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 13 acid damage; P < 4 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 17 acid damage; P < 5 [weakened](../../../condition/weakened.md) (save ends)
        - effect: As a free triggered action, each stone statue and creature [restrained](../../../condition/restrained.md) or [slowed](../../../condition/slowed.md) by Petrify within distance moves up to their speed and uses a [signature ability](../../../rule/combat/signature-ability.md) that gains an edge, targeting an enemy of the medusa's choice. A stone statue without its own statistics has speed 5 and uses the medusa's [free strike](../../../feature/common/main-actions/free-strike.md).
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Stone Puppets
      target: Special
      type: feature
      usage: '-'
free_strike: 8
intuition: 0
keywords:
    - Accursed
    - Humanoid
    - Medusa
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.medusa.statblock/medusa
    source: mcdm.monsters.v1
might: 2
name: Medusa
organization: Solo
presence: 0
reason: 0
role: ""
size: 1M
speed: 10
stability: 5
stamina: "420"
type: statblock
```
