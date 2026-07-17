---
features:
    - body: Each lightbender acting this turn can [teleport](../../movement/teleport.md) up to their speed as a move action and attempt to hide as a free maneuver, all until the start of their next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Silent Prowl
    - body: Each lightbender acting this turn can create a duplicate lightbender in an unoccupied space [adjacent](../../rule/combat/adjacent.md) to them. The duplicate is indistinguishable from the lightbender except by supernatural means, has 1 [Stamina](../../rule/health/stamina.md), and has the lightbender's speed. A duplicate acts on the lightbender's turn but can take only move actions. Once per round before or after using an ability, a lightbender can trade places with any lightbender duplicate.
      cost: 5 Malice
      icon: ⭐️
      name: Duplicate
    - cost: 7 Malice
      icon: ❇️
      intro: Each lightbender in the encounter shines radiantly, distorting the senses of any enemy within 5 squares of them. Each affected enemy makes a **Reason test**.
      name: Everything the Light Touches
      power_roll:
        tiers:
            high: No effect.
            low: The target doesn't have line of effect to any lightbender (save ends).
            mid: The target doesn't have line of effect to any lightbender (EoT).
file_basename: lightbender-malice
file_dpath: monster/lightbender
flavor: At the start of any lightbender's turn, you can spend Malice to activate one of the following features.
item_id: lightbender-malice
item_name: Lightbender Malice
kind: malice
name: Lightbender Malice
scc: mcdm.monsters.v1/monster.lightbender/lightbender-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Each lightbender acting this turn can [teleport](../../movement/teleport.md) up to their speed as a move action and attempt to hide as a free maneuver, all until the start of their next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Silent Prowl
    - body: Each lightbender acting this turn can create a duplicate lightbender in an unoccupied space [adjacent](../../rule/combat/adjacent.md) to them. The duplicate is indistinguishable from the lightbender except by supernatural means, has 1 [Stamina](../../rule/health/stamina.md), and has the lightbender's speed. A duplicate acts on the lightbender's turn but can take only move actions. Once per round before or after using an ability, a lightbender can trade places with any lightbender duplicate.
      cost: 5 Malice
      icon: ⭐️
      name: Duplicate
    - cost: 7 Malice
      icon: ❇️
      intro: Each lightbender in the encounter shines radiantly, distorting the senses of any enemy within 5 squares of them. Each affected enemy makes a **Reason test**.
      name: Everything the Light Touches
      power_roll:
        tiers:
            high: No effect.
            low: The target doesn't have line of effect to any lightbender (save ends).
            mid: The target doesn't have line of effect to any lightbender (EoT).
flavor: At the start of any lightbender's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.lightbender/lightbender-malice
    source: mcdm.monsters.v1
name: Lightbender Malice
type: featureblock
```
