---
agility: 4
ev: "9"
file_basename: war-dog-blackcap
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 4
intuition: 2
item_id: war-dog-blackcap
item_name: War Dog Blackcap
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
might: 1
movement: Teleport
name: War Dog Blackcap
organization: Horde
presence: 0
reason: 4
role: Ambusher
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-blackcap
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "45"
type: statblock
---

```ds-sb
agility: 4
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 4
          tier1: 8 damage
          tier2: 11 damage
          tier3: 12 damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Flesh-Eater Knife
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 20
      effects:
        - effect: '**Effect:** Each target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Ashes to Ashes
      target: Up to three ash clones
      type: feature
      usage: Maneuver
    - effects:
        - effect: An ash clone created by the blackcap has the blackcap's statistics but has 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). Ash clones don't take turns in combat, but they can act when the blackcap allows them to and can move when the blackcap willingly moves.
      feature_type: trait
      icon: ⭐️
      name: Ash Clones
      type: feature
    - effects:
        - effect: When the blackcap or any of their ash clones is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), that creature's loyalty collar explodes, dealing 3d6 poison damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object. If any [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy has A < 3 they are also [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: trait
      icon: ⭐️
      name: Duplicating Loyalty Collar
      type: feature
free_strike: 4
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-blackcap
    source: mcdm.monsters.v1
might: 1
movement: Teleport
name: War Dog Blackcap
organization: Horde
presence: 0
reason: 4
role: Ambusher
size: 1M
speed: 6
stability: 0
stamina: "45"
type: statblock
```
