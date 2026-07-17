---
features:
    - body: The column of blades must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature or object moves [adjacent](../../rule/combat/adjacent.md) to the column of blades.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Spinning Blades** ability.
    - distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Spinning Blades
      power_roll:
        formula: + 2
        tiers:
            high: 9 damage; M < 3 [bleeding](../../condition/bleeding.md) ([save](../../rule/general/saving-throw.md) ends)
            low: 4 damage
            mid: 6 damage; M < 2 [bleeding](../../condition/bleeding.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object moves within distance of the column.
      target: The triggering creature or object
      usage: Free triggered action
    - body: |-
        **Stone Column (+1 EV)** The column is made of stone and has 8 [Stamina](../../rule/health/stamina.md).

        **Metal Column (+1 EV)** The column is made of metal and has 11 [Stamina](../../rule/health/stamina.md).

        **Concealed (+1 EV)** The blades are concealed inside the column, which remains motionless until triggered.

        **Spiked Flails (+4 EV)** Instead of blades, the column is affixed with heavy spiked balls attached by long chains. The **Whirling Flails** ability replaces **Spinning Blades**.
      icon: ⭐️
      name: Upgrades
    - distance: Melee 2
      icon: ❗️
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Whirling Flails
      power_roll:
        tiers:
            high: 11 damage; M < 3 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
            low: 5 damage
            mid: 8 damage; M < 2 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object moves within distance of the column.
      target: The triggering creature or object
      usage: Free triggered action
    - icon: ⭐️
      intro: Allies who [shift](../../movement/shifting.md) don't trigger the column. A creature observing an ally [shift](../../movement/shifting.md) this way can make an **Intuition test** to [shift](../../movement/shifting.md) in imitation of their movements.
      name: Allied Awareness
      power_roll:
        formula: + 2
        tiers:
            high: The creature doesn't trigger the column.
            low: The creature triggers the column and the column's ability gains an edge.
            mid: The creature triggers the column.
file_basename: column-of-blades
file_dpath: dynamic-terrain/mechanisms
flavor: A spinning wooden column is affixed with sharp blades to slash the unwary.
item_id: column-of-blades
item_name: Column of Blades
level: 3
name: Column of Blades
role: Defender
scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/column-of-blades
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "3"
    - name: Stamina
      value: "5"
    - name: Size
      value: 1L
terrain_type: Fortification
type: dynamic-terrain
---

```ds-fb
features:
    - body: The column of blades must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: A creature or object moves [adjacent](../../rule/combat/adjacent.md) to the column of blades.
      icon: ❕
      name: Activate
      sections:
        - label: Effect
          text: The **Spinning Blades** ability.
    - distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Spinning Blades
      power_roll:
        formula: + 2
        tiers:
            high: 9 damage; M < 3 [bleeding](../../condition/bleeding.md) ([save](../../rule/general/saving-throw.md) ends)
            low: 4 damage
            mid: 6 damage; M < 2 [bleeding](../../condition/bleeding.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object moves within distance of the column.
      target: The triggering creature or object
      usage: Free triggered action
    - body: |-
        **Stone Column (+1 EV)** The column is made of stone and has 8 [Stamina](../../rule/health/stamina.md).

        **Metal Column (+1 EV)** The column is made of metal and has 11 [Stamina](../../rule/health/stamina.md).

        **Concealed (+1 EV)** The blades are concealed inside the column, which remains motionless until triggered.

        **Spiked Flails (+4 EV)** Instead of blades, the column is affixed with heavy spiked balls attached by long chains. The **Whirling Flails** ability replaces **Spinning Blades**.
      icon: ⭐️
      name: Upgrades
    - distance: Melee 2
      icon: ❗️
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Whirling Flails
      power_roll:
        tiers:
            high: 11 damage; M < 3 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
            low: 5 damage
            mid: 8 damage; M < 2 [dazed](../../condition/dazed.md) ([save](../../rule/general/saving-throw.md) ends)
      sections:
        - label: Trigger
          text: A creature or object moves within distance of the column.
      target: The triggering creature or object
      usage: Free triggered action
    - icon: ⭐️
      intro: Allies who [shift](../../movement/shifting.md) don't trigger the column. A creature observing an ally [shift](../../movement/shifting.md) this way can make an **Intuition test** to [shift](../../movement/shifting.md) in imitation of their movements.
      name: Allied Awareness
      power_roll:
        formula: + 2
        tiers:
            high: The creature doesn't trigger the column.
            low: The creature triggers the column and the column's ability gains an edge.
            mid: The creature triggers the column.
flavor: A spinning wooden column is affixed with sharp blades to slash the unwary.
level: 3
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.mechanisms/column-of-blades
    source: mcdm.monsters.v1
name: Column of Blades
role: Defender
stats:
    - name: EV
      value: "3"
    - name: Stamina
      value: "5"
    - name: Size
      value: 1L
terrain_type: Fortification
type: dynamic-terrain
```
