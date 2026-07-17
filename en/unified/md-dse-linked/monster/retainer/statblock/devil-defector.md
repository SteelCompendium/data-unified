---
agility: 2
ev: '-'
file_basename: devil-defector
file_dpath: monster/retainer/statblock
free_strike: 5
immunities:
    - Fire 5
intuition: 1
item_id: devil-defector
item_name: Devil Defector
keywords:
    - Devil
    - Infernal
level: 5
might: 3
movement: Fly
name: Devil Defector
organization: Retainer
presence: 2
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.retainer.statblock/devil-defector
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "57"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 6 corruption or fire damage
          tier2: 10 corruption or fire damage
          tier3: 13 corruption or fire damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Black Flame
      target: One creature or object
      type: feature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A sapient enemy is reduced to 0 [Stamina](../../../rule/health/stamina.md).
            **Effect:** The defector makes an offer to keep the target alive. If the target accepts, they are reduced to 1 [Stamina](../../../rule/health/stamina.md) instead. On the target's next turn, the defector controls their move action and the target must use a [signature ability](../../../rule/combat/signature-ability.md) against a creature of the defector's choice or immediately die. To have the target turn down the offer, the Diretor must spend 3 [Malice](../../../rule/monster/malice.md).
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
        - Strike
      name: Tempting Offer
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - effects:
        - effect: If a creature within 10 squares speaks the defector's true name, the defector loses their damage immunities and their Tempting Offer triggered action until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 5
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/devil-defector
    source: mcdm.monsters.v1
might: 3
movement: Fly
name: Devil Defector
organization: Retainer
presence: 2
reason: 3
role: Hexer
size: 1M
speed: 6
stability: 0
stamina: "57"
type: statblock
```
