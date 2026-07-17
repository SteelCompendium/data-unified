---
agility: 2
ev: "4"
file_basename: war-dog-phosphorite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
immunities:
    - Acid 2
intuition: 0
item_id: war-dog-phosphorite
item_name: War Dog Phosphorite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
might: 0
name: War Dog Phosphorite
organization: Horde
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-phosphorite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: No effect.
          tier2: The detonator is disarmed and destroyed.
          tier3: The creature can attach the detonator to another creature or object within 5 squares of them.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Caustic Detonator
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).'
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
        - effect: When the phosphorite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 2
immunities:
    - Acid 2
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-phosphorite
    source: mcdm.monsters.v1
might: 0
name: War Dog Phosphorite
organization: Horde
presence: 0
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "15"
type: statblock
```
