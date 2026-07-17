---
agility: 3
ev: 8 for four minions
file_basename: mindkiller-whelp
file_dpath: monster/voiceless-talker/statblock
free_strike: 3
immunities:
    - Psychic 6
intuition: 1
item_id: mindkiller-whelp
item_name: Mindkiller Whelp
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Fly, hover
name: Mindkiller Whelp
organization: Minion
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller-whelp
size: 1S
source: mcdm.monsters.v1
speed: 4
stability: 0
stamina: "9"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: 3
ev: 8 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage; the target takes a bane on their next strike
          tier3: 7 damage; the target takes a bane on their next strike
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Eager Claws
      target: One creature or object per minion
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The whelp reduces a non-[minion](../../../rule/organization/minion.md) creature to 0 [Stamina](../../../rule/health/stamina.md).
            **Effect:** The whelp transforms into a mindkiller whose [Stamina](../../../rule/health/stamina.md) equals their squad's [Stamina](../../../rule/health/stamina.md) pool before transforming. The [Stamina](../../../rule/health/stamina.md) pool then loses the whelp's [Stamina](../../../rule/health/stamina.md).
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
      name: Feast
      target: Self
      type: feature
      usage: Triggered Action
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) voiceless talker within 5 squares of the whelp uses a psionic ability, they can do so as if they were in the whelp's space.
      feature_type: trait
      icon: ⭐️
      name: Psionic Conductor
      type: feature
free_strike: 3
immunities:
    - Psychic 6
intuition: 1
keywords:
    - Horror
    - Voiceless Talker
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller-whelp
    source: mcdm.monsters.v1
might: -1
movement: Fly, hover
name: Mindkiller Whelp
organization: Minion
presence: 0
reason: 1
role: Hexer
size: 1S
speed: 4
stability: 0
stamina: "9"
type: statblock
with_captain: +2 damage bonus to strikes
```
