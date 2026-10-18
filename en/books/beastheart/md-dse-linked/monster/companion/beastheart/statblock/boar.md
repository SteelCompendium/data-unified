---
agility: 1
companion: boar
file_basename: boar
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
intuition: 2
item_id: boar
item_name: Boar
keywords:
    - Animal
    - Companion
level: 1
might: 2
name: Boar
organization: Companion
presence: 2
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/boar
size: 1M
skills:
    - Search
source: mcdm.beastheart.v1
speed: 5
stability: 2
stamina: = yours
type: statblock
---

```ds-sb
agility: 1
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - effect: The boar moves up to their speed in a straight line. When this movement ends, they can deal damage equal to 3 + their Might score to an adjacent target. If the boar moved closer to the target as part of this movement, the boar deals extra damage equal to their Might score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: The target is [bleeding](../../../../condition/bleeding.md) until the end of their next turn.
      feature_type: ability
      flavor: With an enraged snort, the boar lunges forward to rip open foes with their tusks.
      keywords:
        - Companion
        - Melee
        - Weapon
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.boar.level-1/gore
      name: Gore
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the boar is winded, they have damage immunity equal to their Might score and ignore the effects of [bleeding](../../../../condition/bleeding.md).
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.boar.level-1/spiteful-endurance
      name: Spiteful Endurance
      type: feature
free_strike: 1 + M
intuition: 2
keywords:
    - Animal
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/boar
    source: mcdm.beastheart.v1
might: 2
name: Boar
organization: Companion
presence: 2
reason: -1
role: ""
size: 1M
skills:
    - Search
speed: 5
stability: 2
stamina: = yours
type: statblock
```
