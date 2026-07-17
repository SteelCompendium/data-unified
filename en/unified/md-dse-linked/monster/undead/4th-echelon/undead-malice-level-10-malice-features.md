---
features:
    - body: The [undead](../../../rule/keyword/undead.md) activates a [Malice](../../../rule/monster/malice.md) feature available to [undead](../../../rule/keyword/undead.md) of level 9 or lower.
      cost: 2-7+ Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 7 Malice
      icon: ❇️
      intro: The [undead](../../../rule/keyword/undead.md) attempts to rend the vitality of their foes. Each enemy within 5 squares of the [undead](../../../rule/keyword/undead.md) makes a **Might test**.
      name: Death Tax
      power_roll:
        tiers:
            high: 5 corruption damage
            low: 10 corruption damage; the target loses 2 [Recoveries](../../../rule/health/recoveries.md)
            mid: 8 corruption damage; the target loses 1 [Recovery](../../../rule/health/recoveries.md)
      sections:
        - label: Effect
          text: A target who has fewer [Recoveries](../../../rule/health/recoveries.md) than they would lose is also [weakened](../../../condition/weakened.md) (save ends).
        - label: Special
          text: This ability can't be used by a [minion](../../../rule/organization/minion.md).
file_basename: undead-malice-level-10-malice-features
file_dpath: monster/undead/4th-echelon
flavor: At the start of any level 10 undead's turn, you can spend Malice to activate one of the following features.
item_id: undead-malice-level-10-malice-features
item_name: Undead Malice (Level 10 Malice Features)
kind: malice
level: 10
name: Undead Malice (Level 10 Malice Features)
scc: mcdm.monsters.v1/monster.undead.4th-echelon/undead-malice-level-10-malice-features
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The [undead](../../../rule/keyword/undead.md) activates a [Malice](../../../rule/monster/malice.md) feature available to [undead](../../../rule/keyword/undead.md) of level 9 or lower.
      cost: 2-7+ Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 7 Malice
      icon: ❇️
      intro: The [undead](../../../rule/keyword/undead.md) attempts to rend the vitality of their foes. Each enemy within 5 squares of the [undead](../../../rule/keyword/undead.md) makes a **Might test**.
      name: Death Tax
      power_roll:
        tiers:
            high: 5 corruption damage
            low: 10 corruption damage; the target loses 2 [Recoveries](../../../rule/health/recoveries.md)
            mid: 8 corruption damage; the target loses 1 [Recovery](../../../rule/health/recoveries.md)
      sections:
        - label: Effect
          text: A target who has fewer [Recoveries](../../../rule/health/recoveries.md) than they would lose is also [weakened](../../../condition/weakened.md) (save ends).
        - label: Special
          text: This ability can't be used by a [minion](../../../rule/organization/minion.md).
flavor: At the start of any level 10 undead's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.undead.4th-echelon/undead-malice-level-10-malice-features
    source: mcdm.monsters.v1
name: Undead Malice (Level 10 Malice Features)
type: featureblock
```
