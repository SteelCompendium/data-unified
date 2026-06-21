---
features:
    - body: Each lightbender acting this turn can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to their speed as a move action and attempt to hide as a free maneuver, all until the start of their next turn.
      cost: 3 Malice
      icon: ⭐️
      name: Silent Prowl
    - body: Each lightbender acting this turn can create a duplicate lightbender in an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them. The duplicate is indistinguishable from the lightbender except by supernatural means, has 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), and has the lightbender's speed. A duplicate acts on the lightbender's turn but can take only move actions. Once per round before or after using an ability, a lightbender can trade places with any lightbender duplicate.
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

At the start of any lightbender's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Silent Prowl (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each lightbender acting this turn can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to their speed as a move action and attempt to hide as a free maneuver, all until the start of their next turn.

> ⭐️ **Duplicate (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each lightbender acting this turn can create a duplicate lightbender in an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them. The duplicate is indistinguishable from the lightbender except by supernatural means, has 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), and has the lightbender's speed. A duplicate acts on the lightbender's turn but can take only move actions. Once per round before or after using an ability, a lightbender can trade places with any lightbender duplicate.

> ❇️ **Everything the Light Touches (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each lightbender in the encounter shines radiantly, distorting the senses of any enemy within 5 squares of them. Each affected enemy makes a **Reason test**.
>
> - **≤11:** The target doesn't have line of effect to any lightbender (save ends).
> - **12-16:** The target doesn't have line of effect to any lightbender (EoT).
> - **17+:** No effect.
