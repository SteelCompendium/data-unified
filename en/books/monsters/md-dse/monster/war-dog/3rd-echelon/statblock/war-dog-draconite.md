---
agility: 1
ev: 9 for four minions
file_basename: war-dog-draconite
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 4
intuition: -1
item_id: war-dog-draconite
item_name: War Dog Draconite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
might: 4
name: War Dog Draconite
organization: Minion
presence: 2
reason: -2
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-draconite
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "13"
type: statblock
with_captain: +3 damage bonus to strikes
---

```ds-sb
agility: 1
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 4 damage, 3 psychic damage
          tier3: 4 damage, 4 psychic damage; the target must move their speed in a straight line away from the draconite
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Greatsword and Roar
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the draconite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 4
intuition: -1
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-draconite
    source: mcdm.monsters.v1
might: 4
name: War Dog Draconite
organization: Minion
presence: 2
reason: -2
role: Brute
size: "2"
speed: 5
stability: 2
stamina: "13"
type: statblock
with_captain: +3 damage bonus to strikes
```
