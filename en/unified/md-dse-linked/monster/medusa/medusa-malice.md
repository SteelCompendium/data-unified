---
features:
    - cost: 4 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Weakening Glare
      power_roll:
        formula: + 4
        tiers:
            high: 12 damage; [weakened](../../condition/weakened.md) (save ends)
            low: 6 damage; [weakened](../../condition/weakened.md) (EoT)
            mid: 10 damage; [weakened](../../condition/weakened.md) (EoT)
      target: One creature
      usage: Main action
    - body: The medusa takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 5 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Ssstop and Lisssten
      power_roll:
        formula: + 4
        tiers:
            high: I < 4 the target is charmed
            low: I < 2 the target is charmed
            mid: I < 3 the target is charmed
      sections:
        - label: Effect
          text: At a time of the medusa's choosing, a charmed creature moves up to their speed and makes a [free strike](../../feature/common/main-actions/free-strike.md) against an enemy of the medusa's choice as a free triggered action. The creature is then no longer charmed.
      target: Three creatures
      usage: Main action
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The medusa causes three stone statues within 10 squares of them to each shatter in a 2-cube explosion. Each enemy in one of those areas makes a **Might test**. An enemy [restrained](../../condition/restrained.md) or [slowed](../../condition/slowed.md) by the medusa's Petrify ability has a double bane on the test.
      name: Shatter Victims
      power_roll:
        tiers:
            high: 6 damage
            low: 12 damage; vertical [push](../../movement/forced-movement.md) 3; [bleeding](../../condition/bleeding.md) (save ends)
            mid: 10 damage; vertical [push](../../movement/forced-movement.md) 3
file_basename: medusa-malice
file_dpath: monster/medusa
flavor: At the start of a medusa's turn, you can spend Malice to activate one of the following features.
item_id: medusa-malice
item_name: Medusa Malice
kind: malice
name: Medusa Malice
scc: mcdm.monsters.v1/monster.medusa/medusa-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: 4 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Weakening Glare
      power_roll:
        formula: + 4
        tiers:
            high: 12 damage; [weakened](../../condition/weakened.md) (save ends)
            low: 6 damage; [weakened](../../condition/weakened.md) (EoT)
            mid: 10 damage; [weakened](../../condition/weakened.md) (EoT)
      target: One creature
      usage: Main action
    - body: The medusa takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - cost: 5 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Ssstop and Lisssten
      power_roll:
        formula: + 4
        tiers:
            high: I < 4 the target is charmed
            low: I < 2 the target is charmed
            mid: I < 3 the target is charmed
      sections:
        - label: Effect
          text: At a time of the medusa's choosing, a charmed creature moves up to their speed and makes a [free strike](../../feature/common/main-actions/free-strike.md) against an enemy of the medusa's choice as a free triggered action. The creature is then no longer charmed.
      target: Three creatures
      usage: Main action
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The medusa causes three stone statues within 10 squares of them to each shatter in a 2-cube explosion. Each enemy in one of those areas makes a **Might test**. An enemy [restrained](../../condition/restrained.md) or [slowed](../../condition/slowed.md) by the medusa's Petrify ability has a double bane on the test.
      name: Shatter Victims
      power_roll:
        tiers:
            high: 6 damage
            low: 12 damage; vertical [push](../../movement/forced-movement.md) 3; [bleeding](../../condition/bleeding.md) (save ends)
            mid: 10 damage; vertical [push](../../movement/forced-movement.md) 3
flavor: At the start of a medusa's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.medusa/medusa-malice
    source: mcdm.monsters.v1
name: Medusa Malice
type: featureblock
```
