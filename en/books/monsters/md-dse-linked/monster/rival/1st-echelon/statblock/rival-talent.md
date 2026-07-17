---
agility: 0
ev: "16"
file_basename: rival-talent
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 0
item_id: rival-talent
item_name: Rival Talent
keywords:
    - Humanoid
    - Rival
level: 2
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-talent
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
          tier1: 7 psychic damage; M < 0 [prone](../../../../condition/prone.md)
          tier2: 10 psychic damage; [push](../../../../movement/forced-movement.md) 2; M < 1 [prone](../../../../condition/prone.md)
          tier3: 13 psychic damage; [push](../../../../movement/forced-movement.md) 3; M < 2 [prone](../../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
        - Telekinesis
      name: Reverberating Blast
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: R < 0 [slowed](../../../../condition/slowed.md) (save ends)
          tier2: R < 1 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: R < 2 [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Telepathy
      name: Muddle the Mind
      target: One creature or object
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature deals damage to the talent.
            **Effect:** The talent halves the damage and [shifts](../../../../movement/shifting.md) up to 2 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
      name: Precognitive Shift
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the talent chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the talent and the creature can add a d3 roll to power rolls they make against each other.
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
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-talent
    source: mcdm.monsters.v1
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 2
role: Hexer
size: 1M
speed: 5
stability: 2
stamina: "60"
type: statblock
```
