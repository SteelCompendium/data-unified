---
agility: 3
ev: 6 for four minions
file_basename: war-dog-war-frog
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
immunities:
    - Poison 4
intuition: 2
item_id: war-dog-war-frog
item_name: War Dog War Frog
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 4
might: -1
movement: Climb, swim
name: War Dog War Frog
organization: Minion
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-war-frog
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "8"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 4
      effects:
        - roll: Power Roll + 3
          tier1: 3 poison damage
          tier2: 5 poison damage
          tier3: 7 poison damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Poisoned Dagger
      target: One creature per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the war frog is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
immunities:
    - Poison 4
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-war-frog
    source: mcdm.monsters.v1
might: -1
movement: Climb, swim
name: War Dog War Frog
organization: Minion
presence: 0
reason: 0
role: Ambusher
size: 1S
speed: 5
stability: 0
stamina: "8"
type: statblock
with_captain: +2 bonus to speed
```
