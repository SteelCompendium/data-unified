---
features:
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Slow-Poison Needle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 8 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 12 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: The slow-poison needle is initially painless, with the damage and effect delayed until the start of the target's next turn. If the shade is hidden, using this ability doesn't cause them to be revealed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 10
      name: Shadow Dagger
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 23 poison damage; the target has shadowed vision (save ends)
            low: 12 poison damage; the target has shadowed vision (save ends)
            mid: 17 poison damage; the target has shadowed vision (save ends)
      sections:
        - label: Effect
          text: While a creature has shadowed vision, all creatures have concealment from them.
      target: One creature
      usage: Main action
file_basename: shadow-elf-shade
file_dpath: monster/retainer/advancement-features
item_id: shadow-elf-shade
item_name: Shadow Elf Shade Advancement Features
name: Shadow Elf Shade Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/shadow-elf-shade
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 7
      name: Slow-Poison Needle
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 8 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 12 poison damage; [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: The slow-poison needle is initially painless, with the damage and effect delayed until the start of the target's next turn. If the shade is hidden, using this ability doesn't cause them to be revealed.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 10
      name: Shadow Dagger
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 23 poison damage; the target has shadowed vision (save ends)
            low: 12 poison damage; the target has shadowed vision (save ends)
            mid: 17 poison damage; the target has shadowed vision (save ends)
      sections:
        - label: Effect
          text: While a creature has shadowed vision, all creatures have concealment from them.
      target: One creature
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/shadow-elf-shade
    source: mcdm.monsters.v1
name: Shadow Elf Shade Advancement Features
type: featureblock
```
