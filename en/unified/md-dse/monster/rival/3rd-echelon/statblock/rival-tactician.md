---
agility: 1
ev: "40"
file_basename: rival-tactician
file_dpath: monster/rival/3rd-echelon/statblock
free_strike: 9
intuition: 0
item_id: rival-tactician
item_name: Rival Tactician
keywords:
    - Humanoid
    - Rival
level: 8
might: 4
name: Rival Tactician
organization: Elite
presence: 2
reason: 3
role: Artillery
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-tactician
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "180"
type: statblock
---

```ds-sb
agility: 1
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage
          tier2: 18 damage; A < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 22 damage; A < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Command From the Back
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 15 damage; M < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier2: 21 damage; M < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 26 damage; M < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Safeguard
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An enemy within distance willingly moves.
            **Effect:** At any point during the movement, the tactician uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Quickshot
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the tactician chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the tactician and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 9
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-tactician
    source: mcdm.monsters.v1
might: 4
name: Rival Tactician
organization: Elite
presence: 2
reason: 3
role: Artillery
size: 1M
speed: 5
stability: 2
stamina: "180"
type: statblock
```
