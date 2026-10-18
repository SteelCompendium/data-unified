---
agility: 1
companion: basilisk
file_basename: basilisk
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Poison 3
intuition: 2
item_id: basilisk
item_name: Basilisk
keywords:
    - Beast
    - Companion
level: 1
might: 2
name: Basilisk
organization: Companion
presence: 2
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/basilisk
size: 1L
skills:
    - Alertness
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
      distance: Melee 1 or ranged 5
      effects:
        - effect: The target takes corruption damage equal to 3 + the basilisk's Might score and is stoned (save ends) (see [Stoned](scc.v1:mcdm.beastheart.v1/feature.companion.beastheart.basilisk.level-1/stoned)).
          name: Effect
        - cost: Spend 1 Ferocity
          effect: While stoned this way, the target is also [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).
      feature_type: ability
      flavor: Transfixed by the basilisk's magical gaze or struck by their poisoned claws, the foe's body begins to calcify.
      keywords:
        - Companion
        - Magic
        - Melee
        - Ranged
        - Weapon
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.basilisk.level-1/petrify
      name: Petrify
      target: One enemy
      type: feature
      usage: Maneuver
    - effects:
        - effect: A stoned creature is magically turning to stone. Each time a creature fails the saving throw to end this effect, they take corruption damage equal to the basilisk's Might score. A stoned creature or a creature adjacent to them can use a maneuver to cut the encroaching stone from the stoned target's body, ending the effect and dealing damage to the target equal to twice the basilisk's Might score that can't be reduced in any way. A creature reduced to 0 Stamina while they are stoned, or by an ability that causes a creature to become stoned, is turned to stone until they are restored to life by magical means.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.basilisk.level-1/stoned
      name: Stoned
      type: feature
free_strike: 1 + M
immunities:
    - Poison 3
intuition: 2
keywords:
    - Beast
    - Companion
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/basilisk
    source: mcdm.beastheart.v1
might: 2
name: Basilisk
organization: Companion
presence: 2
reason: -1
role: ""
size: 1L
skills:
    - Alertness
speed: 5
stability: 2
stamina: = yours
type: statblock
```
