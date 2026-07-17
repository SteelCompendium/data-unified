---
agility: 4
ev: "40"
file_basename: rival-shadow
file_dpath: monster/rival/3rd-echelon/statblock
free_strike: 9
intuition: 0
item_id: rival-shadow
item_name: Rival Shadow
keywords:
    - Humanoid
    - Rival
level: 8
might: 0
name: Rival Shadow
organization: Elite
presence: 3
reason: 2
role: Ambusher
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-shadow
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "200"
type: statblock
---

```ds-sb
agility: 4
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage; A < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 18 damage; A < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 22 damage; A < 4 [bleeding](../../../../condition/bleeding.md) and [weakened](../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Assail and Serrate
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The shadow coats their weapon with poison. They have a double edge on their next [strike](../../../../rule/combat/strike.md), and any [potency](../../../../rule/character/potency.md) for that strike increases by 2.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Poison the Blade
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: The shadow deals an extra 9 damage to any target affected by a [condition](../../../../rule/combat/condition.md).
      feature_type: trait
      icon: ⭐️
      name: Exploit Weakness
      type: feature
    - effects:
        - effect: At the start of an encounter, the shadow chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the shadow and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 9
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-shadow
    source: mcdm.monsters.v1
might: 0
name: Rival Shadow
organization: Elite
presence: 3
reason: 2
role: Ambusher
size: 1M
speed: 7
stability: 1
stamina: "200"
type: statblock
```
