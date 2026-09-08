---
agility: 2
ev: "20"
file_basename: war-dog-ground-commander
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 5
intuition: 2
item_id: war-dog-ground-commander
item_name: War Dog Ground Commander
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
might: 3
name: War Dog Ground Commander
organization: Leader
presence: 2
reason: 3
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-ground-commander
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; [pull](../../../../movement/forced-movement.md) 1
          tier2: 12 damage; [pull](../../../../movement/forced-movement.md) 2
          tier3: 15 damage; [pull](../../../../movement/forced-movement.md) 3
        - effect: One ally within 10 squares of the ground commander can make a [free strike](../../../../feature/common/main-actions/free-strike.md).
          name: Effect
        - cost: 1 Malice
          effect: A target who has I < 2 and who is [adjacent](../../../../rule/combat/adjacent.md) to the ground commander after this ability is resolved is [grabbed](../../../../condition/grabbed.md) (save ends). This grab can't be escaped using the Escape Grab maneuver. The ground commander can grab up to two creatures at a time.
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Psionic
        - Ranged
        - Strike
      name: Conditioning Spear
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 10 burst
      effects:
        - effect: Any target who has a loyalty collar is reduced to 0 [Stamina](../../../../rule/health/stamina.md).
          name: Effect
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Highest Posthumous Promotion
      target: Each war dog in the area
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: Even if reduced to 0 [Stamina](../../../../rule/health/stamina.md), the target moves up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md) after the triggering effect is resolved. The target then immediately dies.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Final Orders
      target: One ally
      trigger: The target takes damage, is [forced moved](../../../../movement/forced-movement.md), or is reduced to 0 [Stamina](../../../../rule/health/stamina.md).
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the ground commander can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: When the ground commander is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
    - cost: Villain Action 1
      distance: 10 burst
      effects:
        - effect: Each target can make a ranged [free strike](../../../../feature/common/main-actions/free-strike.md), then immediately use the Charge main action.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Combined Arms
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Ranged 10
      effects:
        - effect: Each ally within 5 squares of the target moves up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against the target. If the target has I < 2, they are [frightened](../../../../condition/frightened.md) of the ground commander (save ends).
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
        - Ranged
      name: Make an Example of Them
      target: One enemy
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 10 burst
      effects:
        - effect: Each target ally [shifts](../../../../movement/shifting.md) up to 2 squares and can use the Grab maneuver. Until the end of the encounter, each target enemy takes a bane on the Escape Grab maneuver.
          name: Effect
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Claim Them for the Body Banks
      target: Each creature in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-ground-commander
    source: mcdm.monsters.v1
might: 3
name: War Dog Ground Commander
organization: Leader
presence: 2
reason: 3
role: ""
size: 1M
speed: 5
stability: 2
stamina: "120"
type: statblock
```
