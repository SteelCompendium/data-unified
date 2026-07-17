---
agility: 4
ev: 12 for four minions
file_basename: war-dog-blood-jumper
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 4
intuition: 3
item_id: war-dog-blood-jumper
item_name: War Dog Blood Jumper
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 5
movement: Fly
name: War Dog Blood Jumper
organization: Minion
presence: 2
reason: 2
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-blood-jumper
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: "15"
type: statblock
with_captain: +3 bonus to speed
---

```ds-sb
agility: 4
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 4 damage
          tier2: 7 damage
          tier3: 9 damage; A < 4 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Jumplance
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If the jumper doesn't end their turn on the ground, they fall [prone](../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Drop Troop
      type: feature
    - effects:
        - effect: When the jumper is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 4
intuition: 3
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-blood-jumper
    source: mcdm.monsters.v1
might: 5
movement: Fly
name: War Dog Blood Jumper
organization: Minion
presence: 2
reason: 2
role: Harrier
size: 1M
speed: 7
stability: 2
stamina: "15"
type: statblock
with_captain: +3 bonus to speed
```
