---
agility: 3
ev: "20"
file_basename: wode-elf-warleader
file_dpath: monster/elf-wode/statblock
free_strike: 5
intuition: 2
item_id: wode-elf-warleader
item_name: Wode Elf Warleader
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
might: 2
movement: Teleport
name: Wode Elf Warleader
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-warleader
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 3
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; M < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 12 damage; M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 15 damage; M < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Wodeblade
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) target can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike), then each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares. A target who has cover or concealment at the end of this shift can attempt to hide at the end of the warleader''s turn.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Fairness Is a Human Concept
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An ally ends their turn.
            **Effect:** The target must not have taken their turn this round. The target takes their turn immediately, and if they have P < 2 they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and take a bane on strikes until the end of their turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Wode Sickness
      target: One enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: End Effect
      type: feature
    - effects:
        - effect: The warleader can attempt to hide at the end of each of their turns.
      feature_type: trait
      icon: ⭐️
      name: Into the Green
      type: feature
    - effects:
        - effect: Abilities targeting the warleader that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - effect: '**Effect:** The warleader uses Wodeblade against each target and gains an edge on the power roll.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: You Will All Witness my Blade
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 5 burst
      effects:
        - effect: '**Effect:** The warleader can use Wodeblade. Each target can then make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Suppressing Volley
      target: Each ally in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 5 burst
      effects:
        - effect: '**Effect:** Each target is invisible until the start of the next round. The warleader then uses Wodeblade.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: Is It Now or Is It Then?
      target: Self and each ally in the area
      type: feature
      usage: '-'
free_strike: 5
intuition: 2
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-warleader
    source: mcdm.monsters.v1
might: 2
movement: Teleport
name: Wode Elf Warleader
organization: Leader
presence: 2
reason: 2
role: ""
size: 1M
speed: 7
stability: 2
stamina: "120"
type: statblock
```
