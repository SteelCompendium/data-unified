---
features:
    - body: The demon activates a [Malice](../../../rule/monster/malice.md) feature available to demons of level 9 or lower.
      cost: 3-7 Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 7 Malice
      icon: ❇️
      intro: One demon acting this turn unleashes their pent-up agony and pain on every non-demon in a 5 burst. Each target makes a **Presence test**.
      name: Soul Flense
      power_roll:
        tiers:
            high: No effect.
            low: 10 corruption damage; the target is soul flensed
            mid: The target is soul flensed
      sections:
        - label: Effect
          text: The demon removes all [conditions](../../../rule/combat/condition.md) and effects on themself that can be ended by a [saving throw](../../../rule/general/saving-throw.md), and transfers all those effects to each creature soul flensed this way.
file_basename: demon-malice-level-10-malice-features
file_dpath: monster/demon/4th-echelon
flavor: At the start of any level 10 or higher demon's turn, you can spend Malice to activate one of the following features.
item_id: demon-malice-level-10-malice-features
item_name: Demon Malice (Level 10+ Malice Features)
kind: malice
level: 10
name: Demon Malice (Level 10+ Malice Features)
scc: mcdm.monsters.v1/monster.demon.4th-echelon/demon-malice-level-10-malice-features
source: mcdm.monsters.v1
type: featureblock
---

At the start of any level 10 or higher demon's turn, you can spend [Malice](../../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Prior Malice Features (3-7 [Malice](../../../rule/monster/malice.md))**
>
> The demon activates a [Malice](../../../rule/monster/malice.md) feature available to demons of level 9 or lower.

> ❇️ **Soul Flense (7 [Malice](../../../rule/monster/malice.md))**
>
> One demon acting this turn unleashes their pent-up agony and pain on every non-demon in a 5 burst. Each target makes a **Presence test**.
>
> - **≤11:** 10 corruption damage; the target is soul flensed
> - **12-16:** The target is soul flensed
> - **17+:** No effect.
>
> **Effect:** The demon removes all [conditions](../../../rule/combat/condition.md) and effects on themself that can be ended by a [saving throw](../../../rule/general/saving-throw.md), and transfers all those effects to each creature soul flensed this way.
