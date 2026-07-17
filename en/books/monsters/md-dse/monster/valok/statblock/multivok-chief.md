---
agility: 1
ev: "44"
file_basename: multivok-chief
file_dpath: monster/valok/statblock
free_strike: 9
intuition: 1
item_id: multivok-chief
item_name: Multivok Chief
keywords:
    - Construct
    - Multivok
    - Soulless
    - Valok
level: 9
might: 4
name: Multivok Chief
organization: Elite
presence: -3
reason: -2
role: Support
scc: mcdm.monsters.v1/monster.valok.statblock/multivok-chief
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "220"
type: statblock
---

```ds-sb
agility: 1
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 18 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 22 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 8
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Pneumatic Punch
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 15 damage; A < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier2: 21 damage; A < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 26 damage; A < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Targeting Beam
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: '**Effect:** The target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and can use a main action.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Chief's Command
      target: One ally
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** The chief or an ally within distance is subject to an effect that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their turn.
            **Effect:** The target gains 15 temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). Each time this triggered action is used, the amount of temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) received decreases by 3 (to a minimum of 0).
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Quick Shield
      target: The triggering creature
      type: feature
      usage: Triggered Action
    - effects:
        - effect: At the start of the chief's turn, each servok within 2 squares of them regains 15 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      feature_type: trait
      icon: ⭐️
      name: Multivok Maintenance
      type: feature
    - effects:
        - effect: The chief's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Crafted to Perfection
      type: feature
    - effects:
        - effect: While the chief isn't [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), or [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
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
    scc: mcdm.monsters.v1/monster.valok.statblock/multivok-chief
    source: mcdm.monsters.v1
might: 4
name: Multivok Chief
organization: Elite
presence: -3
reason: -2
role: Support
size: 1L
speed: 5
stability: 3
stamina: "220"
type: statblock
```
