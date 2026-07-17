---
features:
    - body: A dwarf can destroy one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) object or square of wall for each 3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) spent. Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the destroyed object or square takes the object's Stamina in damage (3 for wood, 6 for stone, or 9 for metal).
      cost: 3 Malice
      icon: "\U0001F464"
      name: Breaching Charge
    - body: Each dwarf acting this turn can automatically climb at full speed while moving. At any point during this movement, they can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      cost: 5 Malice
      icon: ⭐️
      name: Rappelling Barrage
    - cost: 7 Malice
      distance: 10 x 1 line within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Snaring Line
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
            mid: 6 damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
      sections:
        - label: Effect
          text: Each target makes an **Agility test**.
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy in the area
      trailing: The snaring line remains until the end of the encounter. Any enemy who moves into the area for the first time in a round or starts their turn there must make the test.
      usage: Main action
file_basename: dwarf-malice
file_dpath: monster/dwarf
flavor: At the start of any dwarf's turn, you can spend Malice to activate one of the following features.
item_id: dwarf-malice
item_name: Dwarf Malice
kind: malice
name: Dwarf Malice
scc: mcdm.monsters.v1/monster.dwarf/dwarf-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: A dwarf can destroy one [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) object or square of wall for each 3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) spent. Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the destroyed object or square takes the object's Stamina in damage (3 for wood, 6 for stone, or 9 for metal).
      cost: 3 Malice
      icon: "\U0001F464"
      name: Breaching Charge
    - body: Each dwarf acting this turn can automatically climb at full speed while moving. At any point during this movement, they can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      cost: 5 Malice
      icon: ⭐️
      name: Rappelling Barrage
    - cost: 7 Malice
      distance: 10 x 1 line within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Snaring Line
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
            mid: 6 damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
      sections:
        - label: Effect
          text: Each target makes an **Agility test**.
        - label: Special
          text: This ability can't be used by a [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion).
      target: Each enemy in the area
      trailing: The snaring line remains until the end of the encounter. Any enemy who moves into the area for the first time in a round or starts their turn there must make the test.
      usage: Main action
flavor: At the start of any dwarf's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.dwarf/dwarf-malice
    source: mcdm.monsters.v1
name: Dwarf Malice
type: featureblock
```
