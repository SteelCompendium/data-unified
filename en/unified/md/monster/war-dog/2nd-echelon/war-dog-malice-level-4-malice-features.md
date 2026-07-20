---
features:
    - body: The war dog activates a [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) feature available to war dogs of level 3 or lower.
      cost: 3-7 Malice
      icon: ⭐️
      name: Prior Malice Features
    - cost: 5 Malice
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Loyalty Unto Death
      power_roll:
        tiers:
            high: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2'
            low: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; the enemy is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the nearest non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) war dog (save ends)'
            mid: '[Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; the enemy is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the nearest non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) war dog (EoT)'
      sections:
        - label: Effect
          text: Each target who has a loyalty collar [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, then is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). After each target's Loyalty Collar trait is resolved, each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to either target makes a Presence test.
      target: Two war dogs
      usage: Maneuver
flavor: At the start of any level 4 or higher war dog's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 4
name: War Dog Malice (Level 4+ Malice Features)
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon/war-dog-malice-level-4-malice-features
type: featureblock
---

At the start of any level 4 or higher war dog's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Prior [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) Features (3-7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The war dog activates a [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) feature available to war dogs of level 3 or lower.

> 🏹 **Loyalty Unto Death (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |        **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|--------------------:|
> | **📏 Ranged 10**  | **🎯 Two war dogs** |
>
> **Effect:** Each target who has a loyalty collar [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, then is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). After each target's Loyalty Collar trait is resolved, each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to either target makes a Presence test.
>
> - **≤11:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; the enemy is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the nearest non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) war dog (save ends)
> - **12-16:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; the enemy is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the nearest non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) war dog (EoT)
> - **17+:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
