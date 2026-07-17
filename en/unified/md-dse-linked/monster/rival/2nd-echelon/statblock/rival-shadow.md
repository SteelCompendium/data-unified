---
agility: 3
ev: "28"
file_basename: rival-shadow
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 7
intuition: 0
item_id: rival-shadow
item_name: Rival Shadow
keywords:
    - Humanoid
    - Rival
level: 5
might: 0
name: Rival Shadow
organization: Elite
presence: 2
reason: 1
role: Ambusher
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-shadow
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "140"
type: statblock
---

```ds-sb
agility: 3
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage
          tier2: 15 damage; A < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 18 damage; A < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Ambuscade
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The shadow coats their weapon with poison. They gain an edge on their next [strike](../../../../rule/combat/strike.md), and any [potency](../../../../rule/character/potency.md) for that strike increases by 1.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Poison the Blade
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: The shadow deals an extra 7 damage to any [bleeding](../../../../condition/bleeding.md) target.
      feature_type: trait
      icon: ⭐️
      name: Exploit Opening
      type: feature
    - effects:
        - effect: At the start of an encounter, the shadow chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the shadow and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 7
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-shadow
    source: mcdm.monsters.v1
might: 0
name: Rival Shadow
organization: Elite
presence: 2
reason: 1
role: Ambusher
size: 1M
speed: 7
stability: 1
stamina: "140"
type: statblock
```
