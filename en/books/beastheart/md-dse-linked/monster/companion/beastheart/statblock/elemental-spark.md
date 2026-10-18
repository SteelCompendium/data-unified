---
agility: 2
companion: elemental-spark
file_basename: elemental-spark
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Lightning 3
intuition: 2
item_id: elemental-spark
item_name: Elemental Spark
keywords:
    - Companion
    - Elemental
level: 1
might: 2
name: Elemental Spark
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/elemental-spark
size: 1M
skills:
    - Magic
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
        - effect: The target takes lightning damage equal to 2 + the spark's Might score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: The distance increases to melee 5.
      feature_type: ability
      flavor: An arc of lightning crackles from the spark.
      keywords:
        - Companion
        - Magic
        - Melee
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.elemental-spark.level-1/static-shock
      name: Static Shock
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time on a turn that you or the spark deal lightning damage, you gain 1 surge.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.elemental-spark.level-1/electric-surge
      name: Electric Surge
      type: feature
free_strike: 1 + M
immunities:
    - Lightning 3
intuition: 2
keywords:
    - Companion
    - Elemental
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/elemental-spark
    source: mcdm.beastheart.v1
might: 2
name: Elemental Spark
organization: Companion
presence: 1
reason: -1
role: ""
size: 1M
skills:
    - Magic
speed: 7
stability: 1
stamina: = yours
type: statblock
```
