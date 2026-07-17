---
features:
    - cost: Encounter
      distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: Watch Out!
      sections:
        - label: Trigger
          text: The target takes damage from a strike.
        - label: Effect
          text: The retainer [pushes](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target or the attacking creature up to 2 squares. If that moves the mentor out of distance of the strike, the strike has no effect.
      target: The retainer's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: It's Me You Want!
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 7 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)
            mid: 11 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      target: Two creatures
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
      level: 10
      name: Last Stand
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 damage
            low: 8 damage
            mid: 13 damage
      sections:
        - label: Effect
          text: The retainer and their mentor each gain 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina). Additionally, each [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) ally within 2 squares of the retainer can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      target: One enemy
      usage: Main action
file_basename: defender
file_dpath: monster/retainer/role-advancement
item_id: defender
item_name: Defender Abilities
name: Defender Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/defender
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: Watch Out!
      sections:
        - label: Trigger
          text: The target takes damage from a strike.
        - label: Effect
          text: The retainer [pushes](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target or the attacking creature up to 2 squares. If that moves the mentor out of distance of the strike, the strike has no effect.
      target: The retainer's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: It's Me You Want!
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 7 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)
            mid: 11 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      target: Two creatures
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
      level: 10
      name: Last Stand
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 damage
            low: 8 damage
            mid: 13 damage
      sections:
        - label: Effect
          text: The retainer and their mentor each gain 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina). Additionally, each [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) ally within 2 squares of the retainer can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      target: One enemy
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/defender
    source: mcdm.monsters.v1
name: Defender Abilities
type: featureblock
```
