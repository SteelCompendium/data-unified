---
features:
    - cost: Encounter
      distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: '''Scuse Me, Boss'
      sections:
        - label: Trigger
          text: The warrior's mentor is targeted by a strike while within distance.
        - label: Effect
          text: The warrior and the mentor switch places. The warrior is the strike's new target and the strike has a double bane.
      target: The warrior's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Defensive Fighting
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Effect
          text: Until the start of the warrior's next turn, ability rolls against the warrior or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the warrior have a double bane.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Charge
        - Weapon
      level: 10
      name: Whirlwind of Steel
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      target: Each enemy in the area
      usage: Main action
file_basename: human-warrior
file_dpath: monster/retainer/advancement-features
item_id: human-warrior
item_name: Human Warrior Advancement Features
name: Human Warrior Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/human-warrior
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
      name: '''Scuse Me, Boss'
      sections:
        - label: Trigger
          text: The warrior's mentor is targeted by a strike while within distance.
        - label: Effect
          text: The warrior and the mentor switch places. The warrior is the strike's new target and the strike has a double bane.
      target: The warrior's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Defensive Fighting
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Effect
          text: Until the start of the warrior's next turn, ability rolls against the warrior or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the warrior have a double bane.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Charge
        - Weapon
      level: 10
      name: Whirlwind of Steel
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/human-warrior
    source: mcdm.monsters.v1
name: Human Warrior Advancement Features
type: featureblock
```
