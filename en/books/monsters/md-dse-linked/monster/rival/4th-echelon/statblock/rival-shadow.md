---
agility: 5
ev: "48"
file_basename: rival-shadow
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 2
item_id: rival-shadow
item_name: Rival Shadow
keywords:
    - Humanoid
    - Rival
level: 10
might: 0
name: Rival Shadow
organization: Elite
presence: 4
reason: 3
role: Ambusher
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-shadow
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "240"
type: statblock
---

```ds-sb
agility: 5
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; A < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 21 damage; A < 4 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 25 damage; A < 5 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: A Hush of Ash
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The shadow coats their weapon with poison. They have a double edge on their next [strike](../../../../rule/combat/strike.md), any [potency](../../../../rule/character/potency.md) for that strike increases by 2, and if the target has M < 4, they are [weakened](../../../../condition/weakened.md) (save ends).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Envenomed Steel
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: The shadow deals an extra 10 damage to any target affected by a [condition](../../../../rule/combat/condition.md).
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
free_strike: 10
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-shadow
    source: mcdm.monsters.v1
might: 0
name: Rival Shadow
organization: Elite
presence: 4
reason: 3
role: Ambusher
size: 1M
speed: 5
stability: 1
stamina: "240"
type: statblock
```
