---
features:
    - body: One wyvern in the encounter can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them.
      cost: 3 Malice
      icon: "\U0001F5E1"
      name: Simmering Anger
    - body: Until the end of the round, each wyvern in the encounter has a double edge on strikes and can use their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) when making opportunity attacks.
      cost: 5 Malice
      icon: ⭐️
      name: Boiling Fury
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: Every wyvern's anger fills the encounter map with a thick miasma of hatred. Each enemy in the encounter makes an **Intuition test**.
      name: Overflowing Rage
      power_roll:
        tiers:
            high: No effect.
            low: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by the nearest creature or object (save ends). While the target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) this way, power rolls against them have a double edge.
            mid: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by the nearest creature or object (save ends).
file_basename: wyvern-malice
file_dpath: monster/wyvern
flavor: At the start of any wyvern's turn, you can spend Malice to activate one of the following features.
item_id: wyvern-malice
item_name: Wyvern Malice
kind: malice
name: Wyvern Malice
scc: mcdm.monsters.v1/monster.wyvern/wyvern-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: One wyvern in the encounter can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them.
      cost: 3 Malice
      icon: "\U0001F5E1"
      name: Simmering Anger
    - body: Until the end of the round, each wyvern in the encounter has a double edge on strikes and can use their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) when making opportunity attacks.
      cost: 5 Malice
      icon: ⭐️
      name: Boiling Fury
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: Every wyvern's anger fills the encounter map with a thick miasma of hatred. Each enemy in the encounter makes an **Intuition test**.
      name: Overflowing Rage
      power_roll:
        tiers:
            high: No effect.
            low: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by the nearest creature or object (save ends). While the target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) this way, power rolls against them have a double edge.
            mid: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by the nearest creature or object (save ends).
flavor: At the start of any wyvern's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.wyvern/wyvern-malice
    source: mcdm.monsters.v1
name: Wyvern Malice
type: featureblock
```
