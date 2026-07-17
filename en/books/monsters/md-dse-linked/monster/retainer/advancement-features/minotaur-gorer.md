---
features:
    - distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: Horn Toss
      sections:
        - label: Trigger
          text: The gorer damages a creature within distance using Gore.
        - label: Effect
          text: The target is pushed up to 3 squares. If the target has [stability](../../../rule/character/stability.md) 0, they are also knocked [prone](../../../condition/prone.md).
      target: The triggering creature
      usage: Free triggered action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 7
      name: Triumphant Bay
      sections:
        - label: Effect
          text: The gorer gains 3 [surges](../../../rule/resource/surge.md), and until the start of the gorer's next turn, [strikes](../../../rule/combat/strike.md) made against them and their mentor take a bane.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Horn Rake
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; M < STRONG [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends).
            low: 11 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 16 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
file_basename: minotaur-gorer
file_dpath: monster/retainer/advancement-features
item_id: minotaur-gorer
item_name: Minotaur Gorer Advancement Features
name: Minotaur Gorer Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/minotaur-gorer
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: Horn Toss
      sections:
        - label: Trigger
          text: The gorer damages a creature within distance using Gore.
        - label: Effect
          text: The target is pushed up to 3 squares. If the target has [stability](../../../rule/character/stability.md) 0, they are also knocked [prone](../../../condition/prone.md).
      target: The triggering creature
      usage: Free triggered action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 7
      name: Triumphant Bay
      sections:
        - label: Effect
          text: The gorer gains 3 [surges](../../../rule/resource/surge.md), and until the start of the gorer's next turn, [strikes](../../../rule/combat/strike.md) made against them and their mentor take a bane.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Horn Rake
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; M < STRONG [prone](../../../condition/prone.md) and can't stand ([save](../../../rule/general/saving-throw.md) ends).
            low: 11 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 16 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/minotaur-gorer
    source: mcdm.monsters.v1
name: Minotaur Gorer Advancement Features
type: featureblock
```
