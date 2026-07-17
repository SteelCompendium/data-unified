---
agility: 3
ev: "32"
file_basename: mindkiller
file_dpath: monster/voiceless-talker/statblock
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
item_id: mindkiller
item_name: Mindkiller
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Fly, hover
name: Mindkiller
organization: Elite
presence: 0
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "140"
type: statblock
---

```ds-sb
agility: 3
ev: "32"
features:
    - effects:
        - effect: The mindkiller can [grab](../../../condition/grabbed.md) creatures who are size 4 or smaller, using their Reason score in place of Might. A creature [grabbed](../../../condition/grabbed.md) by the mindkiller takes a bane on ability rolls made to escape the grab.
      feature_type: trait
      icon: ⭐️
      name: Brain Latch
      type: feature
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 11 damage
          tier2: 17 damage; A < 2 [grabbed](../../../condition/grabbed.md)
          tier3: 21 damage; A < 3 [grabbed](../../../condition/grabbed.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Killer Claws
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 10 damage; R < 1 the mindkiller is invisible to the target (save ends)
          tier2: 15 damage; R < 2 the mindkiller is invisible to the target (save ends)
          tier3: 18 damage; R < 3 the mindkiller is invisible to the target (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Concealing Strike
      target: Two creatures
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: '**Effect:** The target must be [grabbed](../../../condition/grabbed.md) by the mindkiller. If the target has R < 2, they take a −1 penalty to their Reason, Intuition, or Presence score and the mindkiller has a +1 bonus to the same score, all until the end of the encounter.'
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
      name: Mindwipe
      target: One creature
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The mindkiller takes damage.
            **Effect:** The mindkiller halves the damage. If the mindkiller has a creature [grabbed](../../../condition/grabbed.md), that creature takes the other half of the damage.
            **3 Malice:** A [grabbed](../../../condition/grabbed.md) creature takes the damage instead of the mindkiller.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Meat Shield
      target: Self
      type: feature
      usage: Triggered Action
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) voiceless talker within 5 squares of the mindkiller uses a psionic ability, they can do so as if they were in the mindkiller's space.
      feature_type: trait
      icon: ⭐️
      name: Psionic Conductor
      type: feature
    - effects:
        - effect: The mindkiller can move through enemies' spaces at their usual speed.
      feature_type: trait
      icon: ⭐️
      name: Nimble
      type: feature
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Horror
    - Voiceless Talker
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Mindkiller
organization: Elite
presence: 0
reason: 3
role: Hexer
size: 1S
speed: 6
stability: 2
stamina: "140"
type: statblock
```
