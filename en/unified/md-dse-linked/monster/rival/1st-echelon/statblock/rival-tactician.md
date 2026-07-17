---
agility: 0
ev: "16"
file_basename: rival-tactician
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 0
item_id: rival-tactician
item_name: Rival Tactician
keywords:
    - Humanoid
    - Rival
level: 2
might: 2
name: Rival Tactician
organization: Elite
presence: 0
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-tactician
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "60"
type: statblock
---

```ds-sb
agility: 0
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage
          tier3: 14 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Dual Targeting Shot
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage; M < 0 [weakened](../../../../condition/weakened.md) (save ends)
          tier2: 13 damage; M < 1 [weakened](../../../../condition/weakened.md) (save ends)
          tier3: 16 damage; M < 2 [weakened](../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: I'll Cover You!
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An enemy within distance willingly moves.
            **Effect:** At any point during the movement, the tactician makes a [free strike](../../../../feature/common/main-actions/free-strike.md) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Overwatch
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the tactician chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the tactician and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-tactician
    source: mcdm.monsters.v1
might: 2
name: Rival Tactician
organization: Elite
presence: 0
reason: 1
role: Artillery
size: 1M
speed: 5
stability: 2
stamina: "60"
type: statblock
```
