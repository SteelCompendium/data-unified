---
features:
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 7
      name: Looming Wings
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 corruption damage; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 5 corruption damage; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 9 corruption damage; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: If the Nameless's mentor is in the area, ability rolls against the mentor have a double bane until the start of their next turn.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 5 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 10
      name: Spew Death
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 corruption damage
            low: 11 corruption damage
            mid: 16 corruption damage
      sections:
        - label: Special
          text: The Nameless must be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) to use this ability.
        - label: Effect
          text: Any living [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by this ability regain all their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and become corporeal [undead](scc.v1:mcdm.monsters.v1/rule.keyword/undead) under the Nameless's control until the end of the Nameless's next turn, after which they are destroyed.
      target: Each enemy in the area
      usage: Main action
file_basename: the-nameless
file_dpath: monster/retainer/advancement-features
item_id: the-nameless
item_name: The Nameless Advancement Features
name: The Nameless Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/the-nameless
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 7
      name: Looming Wings
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 corruption damage; I < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 5 corruption damage; I < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 9 corruption damage; I < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: If the Nameless's mentor is in the area, ability rolls against the mentor have a double bane until the start of their next turn.
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: 5 burst
      icon: ❇️
      keywords:
        - Area
        - Magic
      level: 10
      name: Spew Death
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 corruption damage
            low: 11 corruption damage
            mid: 16 corruption damage
      sections:
        - label: Special
          text: The Nameless must be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) to use this ability.
        - label: Effect
          text: Any living [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by this ability regain all their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and become corporeal [undead](scc.v1:mcdm.monsters.v1/rule.keyword/undead) under the Nameless's control until the end of the Nameless's next turn, after which they are destroyed.
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/the-nameless
    source: mcdm.monsters.v1
name: The Nameless Advancement Features
type: featureblock
```
