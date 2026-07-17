---
agility: 1
ev: "3"
file_basename: kobold-adeptus
file_dpath: monster/kobold/statblock
free_strike: 2
intuition: 0
item_id: kobold-adeptus
item_name: Kobold Adeptus
keywords:
    - Humanoid
    - Kobold
level: 1
might: 0
name: Kobold Adeptus
organization: Horde
presence: 0
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-adeptus
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 4 lightning damage
          tier2: 6 lightning damage
          tier3: 7 lightning damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Shocking Bolt
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 5 damage
          tier3: 6 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Arcane Telum
      target: Three creatures or objects
      type: feature
      usage: Maneuver
    - effects:
        - effect: While [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an ally who also has this trait, the adeptus has stability 1, has cover, and grants cover to allies.
      feature_type: trait
      icon: ⭐️
      name: Shield? Shield!
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-adeptus
    source: mcdm.monsters.v1
might: 0
name: Kobold Adeptus
organization: Horde
presence: 0
reason: 2
role: Artillery
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
```
