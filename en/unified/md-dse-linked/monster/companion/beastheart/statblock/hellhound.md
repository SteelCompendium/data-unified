---
agility: 2
companion: hellhound
file_basename: hellhound
file_dpath: monster/companion/beastheart/statblock
free_strike: 1 + M
immunities:
    - Fire 3
intuition: 2
item_id: hellhound
item_name: Hellhound
keywords:
    - Companion
    - Infernal
level: 1
might: 2
name: Hellhound
organization: Companion
presence: 1
reason: -1
scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/hellhound
size: 1M
skills:
    - Intimidate
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
      distance: Melee 1 or Ranged 2
      effects:
        - effect: The target takes fire damage equal to 3 + the hellhound's Might score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: This ability gains a bonus to either its damage or distance equal to the hellhound's Intuition score.
      feature_type: ability
      flavor: The hellhound exhales infernal flames.
      keywords:
        - Companion
        - Magic
        - Melee
        - Ranged
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.ability.companion.beastheart.hellhound.level-1/fire-breath
      name: Fire Breath
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: You have fire immunity equal to the hellhound's fire immunity.
      feature_type: feature
      metadata:
        scc:
            - mcdm.beastheart.v1/feature.companion.beastheart.hellhound.level-1/hellish-pact
      name: Hellish Pact
      type: feature
free_strike: 1 + M
immunities:
    - Fire 3
intuition: 2
keywords:
    - Companion
    - Infernal
level: 1
metadata:
    scc: mcdm.beastheart.v1/monster.companion.beastheart.statblock/hellhound
    source: mcdm.beastheart.v1
might: 2
name: Hellhound
organization: Companion
presence: 1
reason: -1
role: ""
size: 1M
skills:
    - Intimidate
speed: 7
stability: 1
stamina: = yours
type: statblock
```
