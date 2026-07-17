---
agility: 0
ev: "9"
file_basename: chimeron
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 5
intuition: 1
item_id: chimeron
item_name: Chimeron
keywords:
    - Abyssal
    - Demon
level: 9
might: 4
name: Chimeron
organization: Horde
presence: 2
reason: 2
role: Brute
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/chimeron
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "90"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 9 cold, fire, or sonic damage
          tier2: 11 cold, fire, or sonic damage
          tier3: 13 cold, fire, or sonic damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), or [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Flux Gnash
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The chimeron is targeted by a damage-dealing strike.
            **Effect:** The chimeron halves the damage.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Pain Absorption
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: While the chimeron is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the chimeron can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Abyssal
    - Demon
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/chimeron
    source: mcdm.monsters.v1
might: 4
name: Chimeron
organization: Horde
presence: 2
reason: 2
role: Brute
size: "3"
speed: 6
stability: 2
stamina: "90"
type: statblock
weaknesses:
    - Holy 5
```
