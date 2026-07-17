---
agility: 2
ev: "12"
file_basename: human-blackguard
file_dpath: monster/human/statblock
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
item_id: human-blackguard
item_name: Human Blackguard
keywords:
    - Human
    - Humanoid
level: 1
might: 3
name: Human Blackguard
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.human.statblock/human-blackguard
size: 1M
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
      distance: 1 burst
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 6 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 8 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Zweihander Swing
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** The target is marked until the start of the blackguard''s next turn. The blackguard and each of their allies gain an edge on abilities used against targets marked by the blackguard.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: You!
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the end of each of their turns, the blackguard can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: The blackguard ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature makes a strike against the blackguard or an ally [adjacent](../../../rule/combat/adjacent.md) to them.
            **Effect:** The damage is halved.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Parry!
      target: Self or one ally
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: Self
      effects:
        - effect: '**Effect:** The blackguard [shifts](../../../movement/shifting.md) up to their speed. During or after this movement, they can use their Zweihander Swing twice.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Advance!
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - effect: '**Effect:** The blackguard [slides](../../../movement/forced-movement.md) each target up to 5 squares.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Back!
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 3 cube within 5
      effects:
        - effect: '**Effect:** The blackguard uses their Zweihander Swing against each target. Each ally within 5 squares of the area can then make a [free strike](../../../feature/common/main-actions/free-strike.md) against a target (one target per ally).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Ranged
        - Weapon
      name: I Can Throw My Blade and So Should You!
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-blackguard
    source: mcdm.monsters.v1
might: 3
name: Human Blackguard
organization: Leader
presence: 2
reason: 2
role: ""
size: 1M
speed: 5
stability: 2
stamina: "80"
type: statblock
```
