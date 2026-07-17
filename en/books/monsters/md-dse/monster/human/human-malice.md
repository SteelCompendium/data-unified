---
features:
    - cost: 3 Malice
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Alchemical Device
      power_roll:
        formula: + 2
        tiers:
            high: 9 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            low: 4 corruption damage; A < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
            mid: 6 corruption damage; A < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      sections:
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy and object in the area
      usage: Maneuver
    - body: Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.
      cost: 5 Malice
      icon: ⭐️
      name: Exploit Opening
    - body: Each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) human in the encounter regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 times their level.
      cost: 7 Malice
      icon: ⭐️
      name: Staying Power
file_basename: human-malice
file_dpath: monster/human
flavor: At the start of any human's turn, you can spend Malice to activate one of the following features.
item_id: human-malice
item_name: Human Malice
kind: malice
name: Human Malice
scc: mcdm.monsters.v1/monster.human/human-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: 3 Malice
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Alchemical Device
      power_roll:
        formula: + 2
        tiers:
            high: 9 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            low: 4 corruption damage; A < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
            mid: 6 corruption damage; A < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      sections:
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy and object in the area
      usage: Maneuver
    - body: Each human acting this turn gains an edge on abilities until the end of their turn, or has a double edge on any ability that targets an enemy affected by a condition.
      cost: 5 Malice
      icon: ⭐️
      name: Exploit Opening
    - body: Each non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) human in the encounter regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to 5 times their level.
      cost: 7 Malice
      icon: ⭐️
      name: Staying Power
flavor: At the start of any human's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.human/human-malice
    source: mcdm.monsters.v1
name: Human Malice
type: featureblock
```
