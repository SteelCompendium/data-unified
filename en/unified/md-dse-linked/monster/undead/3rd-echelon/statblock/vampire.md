---
agility: 2
ev: "9"
file_basename: vampire
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: vampire
item_name: Vampire
keywords:
    - Undead
    - Vampire
level: 7
might: 4
movement: Climb
name: Vampire
organization: Horde
presence: 1
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; M < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 10 corruption damage; M < 3 5 corruption damage and [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 11 corruption damage; M < 4 7 corruption damage and [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Exsanguinating Bite
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 7 damage; A < 2 [slowed](../../../../condition/slowed.md) (save ends)
          tier2: 10 damage; A < 3 [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 11 damage; A < 4 [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Vicious Pursuit
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** A creature makes a [strike](../../../../rule/combat/strike.md) against the vampire.
            **Effect:** The target becomes the new target of the [strike](../../../../rule/combat/strike.md).
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Reactive Charm
      target: One enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: The vampire has speed 10 while any creature within 10 squares of them is [bleeding](../../../../condition/bleeding.md). The vampire must make a [strike](../../../../rule/combat/strike.md) against a [bleeding](../../../../condition/bleeding.md) creature on their turn if they are able to.
      feature_type: trait
      icon: ⭐️
      name: Unslakable Bloodthirst
      type: feature
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
keywords:
    - Undead
    - Vampire
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire
    source: mcdm.monsters.v1
might: 4
movement: Climb
name: Vampire
organization: Horde
presence: 1
reason: 1
role: Hexer
size: 1M
speed: 6
stability: 3
stamina: "40"
type: statblock
```
