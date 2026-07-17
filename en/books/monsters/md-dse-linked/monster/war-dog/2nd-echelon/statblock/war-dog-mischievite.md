---
agility: 3
ev: "7"
file_basename: war-dog-mischievite
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: 2
item_id: war-dog-mischievite
item_name: War Dog Mischievite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
might: 1
name: War Dog Mischievite
organization: Horde
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-mischievite
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "35"
type: statblock
---

```ds-sb
agility: 3
ev: "7"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage
          tier2: 7 damage
          tier3: 8 damage; R < 3 the target is dazzled (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Fuse-Iron Knives
      target: Two creatures
      type: feature
      usage: Main action
    - distance: Ranged 3
      effects:
        - effect: |-
            **Effect:** The mischievite swaps positions with the target. An ally targeted by this ability can make a [free strike](../../../../feature/common/main-actions/free-strike.md) before or after being swapped.
            **2 [Malice](../../../../rule/monster/malice.md):** The mischievite can use this ability as a [triggered action](../../../../rule/combat/triggered-action.md) when they are targeted by an ability. If they do, the swapped target becomes the new target of the triggering ability.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Misdirection
      target: One ally or dazzled creature
      type: feature
      usage: Maneuver
    - effects:
        - effect: The mischievite doesn't provoke opportunity attacks by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
    - effects:
        - effect: When the mischievite is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-mischievite
    source: mcdm.monsters.v1
might: 1
name: War Dog Mischievite
organization: Horde
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "35"
type: statblock
```
