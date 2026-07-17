---
features:
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Backfire Curse
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 7 corruption damage; the target is cursed (EoT)
            low: 2 corruption damage; the target is cursed (EoT)
            mid: 5 corruption damage; the target is cursed (EoT)
      sections:
        - label: Effect
          text: While the target is cursed this way, whenever they make a strike that targets only one creature, the retainer can use a free triggered action to choose a second target for the strike within its distance.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Take Root
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; M < STRONG [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 damage; M < WEAK [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: While the target is [slowed](../../../condition/slowed.md) this way, if they end their turn without moving on that turn, they are no longer [slowed](../../../condition/slowed.md) and are [restrained](../../../condition/restrained.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 10
      name: Mazed
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; if the target has M < STRONG they are mazed (save ends)
            low: 7 damage; if the target has M < WEAK they are mazed (save ends)
            mid: 11 damage; if the target has M < AVERAGE they are mazed (save ends)
      sections:
        - label: Effect
          text: While mazed, the target is [dazed](../../../condition/dazed.md). Additionally, at the end of each of the mazed target's turns, the retainer can cause the target to move up to their speed in a straight line in a direction of the retainer's choice. This is not [forced movement](../../../movement/forced-movement.md), and the movement ends if it would cause the target to enter [difficult](../../../movement/difficult-terrain.md) or damaging terrain.
      target: One creature
      usage: Main action
file_basename: hexer
file_dpath: monster/retainer/role-advancement
item_id: hexer
item_name: Hexer Abilities
name: Hexer Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/hexer
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Backfire Curse
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 7 corruption damage; the target is cursed (EoT)
            low: 2 corruption damage; the target is cursed (EoT)
            mid: 5 corruption damage; the target is cursed (EoT)
      sections:
        - label: Effect
          text: While the target is cursed this way, whenever they make a strike that targets only one creature, the retainer can use a free triggered action to choose a second target for the strike within its distance.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Take Root
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 12 damage; M < STRONG [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 5 damage; M < WEAK [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 9 damage; M < AVERAGE [slowed](../../../condition/slowed.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: While the target is [slowed](../../../condition/slowed.md) this way, if they end their turn without moving on that turn, they are no longer [slowed](../../../condition/slowed.md) and are [restrained](../../../condition/restrained.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 10
      name: Mazed
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; if the target has M < STRONG they are mazed (save ends)
            low: 7 damage; if the target has M < WEAK they are mazed (save ends)
            mid: 11 damage; if the target has M < AVERAGE they are mazed (save ends)
      sections:
        - label: Effect
          text: While mazed, the target is [dazed](../../../condition/dazed.md). Additionally, at the end of each of the mazed target's turns, the retainer can cause the target to move up to their speed in a straight line in a direction of the retainer's choice. This is not [forced movement](../../../movement/forced-movement.md), and the movement ends if it would cause the target to enter [difficult](../../../movement/difficult-terrain.md) or damaging terrain.
      target: One creature
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/hexer
    source: mcdm.monsters.v1
name: Hexer Abilities
type: featureblock
```
