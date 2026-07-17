---
agility: 2
ev: "48"
file_basename: rival-tactician
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 0
item_id: rival-tactician
item_name: Rival Tactician
keywords:
    - Humanoid
    - Rival
level: 10
might: 5
name: Rival Tactician
organization: Elite
presence: 3
reason: 4
role: Artillery
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-tactician
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "220"
type: statblock
---

```ds-sb
agility: 2
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage
          tier2: 21 damage; A < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
          tier3: 25 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); A < 5 can't stand (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Forward Assault
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 5
          tier1: 10 damage; M < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier2: 16 damage; M < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 20 damage; M < 5 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Guardian From Afar
      target: One creature in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** An enemy within distance willingly moves.
            **Effect:** At any point during the movement, the tactician and one ally within distance can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Battlefield Control
      target: The triggering enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the tactician chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the tactician and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 10
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-tactician
    source: mcdm.monsters.v1
might: 5
name: Rival Tactician
organization: Elite
presence: 3
reason: 4
role: Artillery
size: 1M
speed: 5
stability: 2
stamina: "220"
type: statblock
```
