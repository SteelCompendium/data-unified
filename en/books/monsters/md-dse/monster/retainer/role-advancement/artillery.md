---
features:
    - distance: Ranged 5
      icon: ❗️
      keywords:
        - Ranged
        - Weapon
      level: 4
      name: Supporting Volley
      sections:
        - label: Trigger
          text: The retainer's mentor makes a strike against a creature within distance.
        - label: Effect
          text: The retainer makes a ranged [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
      target: The triggering creature
      usage: Triggered action
    - cost: Encounter
      distance: 10 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      level: 7
      name: Line 'Em Up
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 7 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 11 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Ricochet Shot
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 19 damage
            low: 9 damage
            mid: 14 damage
      sections:
        - label: Effect
          text: The retainer can target a second creature or object within 5 squares of the original target and that has line of effect to the original target. The retainer doesn't need line of effect to the second target but must be aware of their location.
      target: One creature or object
      usage: Main action
file_basename: artillery
file_dpath: monster/retainer/role-advancement
item_id: artillery
item_name: Artillery Abilities
name: Artillery Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/artillery
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - distance: Ranged 5
      icon: ❗️
      keywords:
        - Ranged
        - Weapon
      level: 4
      name: Supporting Volley
      sections:
        - label: Trigger
          text: The retainer's mentor makes a strike against a creature within distance.
        - label: Effect
          text: The retainer makes a ranged [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
      target: The triggering creature
      usage: Triggered action
    - cost: Encounter
      distance: 10 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      level: 7
      name: Line 'Em Up
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 7 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 11 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Ricochet Shot
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 19 damage
            low: 9 damage
            mid: 14 damage
      sections:
        - label: Effect
          text: The retainer can target a second creature or object within 5 squares of the original target and that has line of effect to the original target. The retainer doesn't need line of effect to the second target but must be aware of their location.
      target: One creature or object
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/artillery
    source: mcdm.monsters.v1
name: Artillery Abilities
type: featureblock
```
