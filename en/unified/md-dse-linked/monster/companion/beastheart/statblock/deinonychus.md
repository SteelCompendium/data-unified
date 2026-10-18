---
agility: 2
companion: deinonychus
file_basename: deinonychus
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
intuition: 2
item_id: deinonychus
item_name: Deinonychus
keywords:
    - Animal
    - Companion
level: 1
might: 2
name: Deinonychus
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/deinonychus
size: 1M
skills:
    - Track
source: mcdm.beastheart.v1
speed: 7
stability: 1
stamina: = yours
type: statblock
---

```ds-sb
agility: 2
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - effect: The target takes damage equal to 3 + the deinonychus's Might score, and if they have M < AVERAGE, they are [bleeding](../../../../condition/bleeding.md) until the end of their next turn.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: A target who has M < STRONG is [bleeding](../../../../condition/bleeding.md) (save ends).
      feature_type: ability
      flavor: The deinonychus kicks their prey, then slashes them with wicked claws.
      keywords:
        - Companion
        - Melee
        - Weapon
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.deinonychus.level-1/terrible-claws
      name: Terrible Claws
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever the deinonychus deals damage to a [bleeding](../../../../condition/bleeding.md) creature, they gain 1 surge.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.deinonychus.level-1/blood-frenzy
      name: Blood Frenzy
      type: feature
free_strike: 1 + M
intuition: 2
keywords:
    - Animal
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/deinonychus
    source: mcdm.beastheart.v1
might: 2
name: Deinonychus
organization: Companion
presence: 1
reason: -1
role: ""
size: 1M
skills:
    - Track
speed: 7
stability: 1
stamina: = yours
type: statblock
```
