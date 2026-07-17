---
agility: 5
ev: "36"
file_basename: vampire-lord
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 7
immunities:
    - Corruption 9
    - poison 9
intuition: 1
item_id: vampire-lord
item_name: Vampire Lord
keywords:
    - Undead
    - Vampire
level: 7
might: 2
movement: Climb, hover, teleport
name: Vampire Lord
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire-lord
size: 1M
source: mcdm.monsters.v1
speed: 12
stability: 3
stamina: "200"
type: statblock
---

```ds-sb
agility: 5
ev: "36"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 13 corruption damage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 21 corruption damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 24 corruption damage; M < 5 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Crimson Embrace
      target: One creature
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Two blood-starved vampires appear in unoccupied spaces within distance.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Arise, My Children
      target: Special
      type: feature
      usage: Maneuver
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** A creature makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the vampire.
            **Effect:** The target becomes the new target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Redirected Charm
      target: One enemy
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The vampire has speed 15 and an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on power rolls while any creature within 20 squares of them is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding). Any [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) creature within 5 squares of the vampire can't hide.
      feature_type: trait
      icon: ⭐️
      name: Lord's Bloodthirst
      type: feature
    - cost: Villain Action 1
      distance: 20 burst
      effects:
        - effect: '**Effect:** Each target who has P < 4 is now [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Ranged
      name: Let Us Feast!
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - roll: Power Roll + 5
          tier1: 2 damage; M < 3 6 corruption damage
          tier2: 7 damage; M < 4 6 corruption damage
          tier3: 10 damage; M < 5 6 corruption damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Red Mist Rising
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Ranged 20
      effects:
        - roll: ""
          tier1: 11 corruption damage
          tier2: 8 corruption damage
          tier3: 2 corruption damage
      feature_type: ability
      icon: ☠️
      keywords:
        - Magic
        - Ranged
      name: Sacrifice
      target: Each chosen ally
      type: feature
      usage: '-'
free_strike: 7
immunities:
    - Corruption 9
    - poison 9
intuition: 1
keywords:
    - Undead
    - Vampire
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire-lord
    source: mcdm.monsters.v1
might: 2
movement: Climb, hover, teleport
name: Vampire Lord
organization: Leader
presence: 2
reason: 1
role: ""
size: 1M
speed: 12
stability: 3
stamina: "200"
type: statblock
```
