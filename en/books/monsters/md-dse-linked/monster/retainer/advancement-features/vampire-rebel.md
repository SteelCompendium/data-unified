---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Blood Surge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: Before the [strike](../../../rule/combat/strike.md), the vampire rebel [shifts](../../../movement/shifting.md) up to their speed. If the vampire rebel has [temporary Stamina](../../../rule/health/temporary-stamina.md), they can expend it, dealing an extra 2 corruption damage for each point of [temporary Stamina](../../../rule/health/temporary-stamina.md) expended this way.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 10
      name: Exsanguination
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 corruption damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 corruption damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 corruption damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
file_basename: vampire-rebel
file_dpath: monster/retainer/advancement-features
item_id: vampire-rebel
item_name: Vampire Rebel Advancement Features
name: Vampire Rebel Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/vampire-rebel
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Blood Surge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: Before the [strike](../../../rule/combat/strike.md), the vampire rebel [shifts](../../../movement/shifting.md) up to their speed. If the vampire rebel has [temporary Stamina](../../../rule/health/temporary-stamina.md), they can expend it, dealing an extra 2 corruption damage for each point of [temporary Stamina](../../../rule/health/temporary-stamina.md) expended this way.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 10
      name: Exsanguination
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 corruption damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 corruption damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 corruption damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.advancement-features/vampire-rebel
    source: mcdm.monsters.v1
name: Vampire Rebel Advancement Features
type: featureblock
```
