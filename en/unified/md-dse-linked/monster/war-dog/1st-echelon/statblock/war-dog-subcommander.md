---
agility: 0
ev: "4"
file_basename: war-dog-subcommander
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
intuition: 0
item_id: war-dog-subcommander
item_name: War Dog Subcommander
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
might: 2
name: War Dog Subcommander
organization: Horde
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-subcommander
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 0
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Command Saber
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Posthumous Promotion
      target: One war dog
      type: feature
      usage: Maneuver
    - effects:
        - effect: Each ally within 5 squares of the subcommander gains a +3 bonus to stability.
      feature_type: trait
      icon: ⭐️
      name: The Iron Saint Does Not Recognize Retreat
      type: feature
    - effects:
        - effect: When the subcommander is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-subcommander
    source: mcdm.monsters.v1
might: 2
name: War Dog Subcommander
organization: Horde
presence: 1
reason: 0
role: Support
size: 1M
speed: 5
stability: 0
stamina: "20"
type: statblock
```
