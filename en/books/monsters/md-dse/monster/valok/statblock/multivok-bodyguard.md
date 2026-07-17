---
agility: 0
ev: "44"
file_basename: multivok-bodyguard
file_dpath: monster/valok/statblock
free_strike: 9
intuition: 1
item_id: multivok-bodyguard
item_name: Multivok Bodyguard
keywords:
    - Construct
    - Multivok
    - Soulless
    - Valok
level: 9
might: 4
name: Multivok Bodyguard
organization: Elite
presence: -4
reason: -2
role: Defender
scc: mcdm.monsters.v1/monster.valok.statblock/multivok-bodyguard
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 5
stamina: "240"
type: statblock
---

```ds-sb
agility: 0
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage
          tier2: 18 damage
          tier3: 22 damage; A < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Gatling Bolt Gun
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 15 damage; M < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier2: 21 damage; M < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 26 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); M < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Valiar Axe
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 10 burst
      effects:
        - effect: |-
            **Special:** This ability targets only metal-clad enemies and metal objects of size 3 or smaller.
            **Effect:** Each target is [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 8 squares, or if they have M < 3, they are [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 15 squares. The bodyguard can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each target who ends this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them.
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Magnetic Pull
      target: Each enemy and object in the area
      type: feature
      usage: Maneuver
    - distance: Melee 2
      effects:
        - effect: |-
            **Trigger:** One ally within distance is targeted by an enemy's ability. The bodyguard can use this ability after seeing the outcome of the power roll.
            **Effect:** The bodyguard becomes the triggering ability's target instead.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Valiar Cloak
      target: Self
      type: feature
      usage: Triggered Action
    - effects:
        - effect: At the start of the bodyguard's turn, each servok within 2 squares of them regains 15 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      feature_type: trait
      icon: ⭐️
      name: Multivok Maintenance
      type: feature
    - effects:
        - effect: The bodyguard's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Crafted to Perfection
      type: feature
    - effects:
        - effect: While the bodyguard isn't [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), or [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
      feature_type: trait
      icon: ⭐️
      name: Valiar Might
      type: feature
free_strike: 9
intuition: 1
keywords:
    - Construct
    - Multivok
    - Soulless
    - Valok
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.valok.statblock/multivok-bodyguard
    source: mcdm.monsters.v1
might: 4
name: Multivok Bodyguard
organization: Elite
presence: -4
reason: -2
role: Defender
size: "2"
speed: 5
stability: 5
stamina: "240"
type: statblock
```
