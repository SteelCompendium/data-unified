---
features:
    - body: Until the end of the round, each rival can impose a bane on a [strike](scc:mcdm.heroes.v1/rule.combat/strike) made against an [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) rival as a free triggered action.
      cost: 3 Malice
      icon: ⭐️
      name: Work as One
    - body: Until the end of the round, whenever any rival makes a power roll against the target of their Rivalry trait, they roll a d3 and add it to the power roll.
      cost: 3 Malice
      icon: ⭐️
      name: We Just Do It Better
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: 'One rival pulls out a magic consumable and hurls it, targeting a 5 x 1 line within 1 square of them or a 3 cube within 10 squares of them. Each enemy in the area makes an Agility test. The rival chooses a damage type and a condition for the outcome of the test from one of the following pairs: sonic damage and [dazed](scc:mcdm.heroes.v1/condition/dazed), poison damage and [weakened](scc:mcdm.heroes.v1/condition/weakened), or fire damage and [frightened](scc:mcdm.heroes.v1/condition/frightened).'
      name: Check Out Our Loot
      power_roll:
        tiers:
            high: 5 damage
            low: 11 damage; the condition affects the target (save ends)
            mid: 8 damage; the condition affects the target (EoT)
    - body: Each rival regains 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina). Until the end of the round, whenever a rival uses an ability against an enemy, each other rival [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to that enemy can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      cost: 7 Malice
      icon: ⭐️
      name: Calling the Shots
    - body: Each rival moves up to their speed and uses a main action or maneuver that doesn't cost [Malice](scc:mcdm.monsters.v1/rule.monster/malice).
      cost: 10 Malice
      icon: ⭐️
      name: Coordinated Takedown
flavor: At the start of any rival's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 1
name: Rival Malice (Level 1+ Malice Features)
scc: mcdm.monsters.v1/monster.rivals/rival-malice-level-1-malice-features
type: featureblock
---

At the start of any rival's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Work as One (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, each rival can impose a bane on a [strike](scc:mcdm.heroes.v1/rule.combat/strike) made against an [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) rival as a free triggered action.

> ⭐️ **We Just Do It Better (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, whenever any rival makes a power roll against the target of their Rivalry trait, they roll a d3 and add it to the power roll.

> 🔳 **Check Out Our Loot (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> One rival pulls out a magic consumable and hurls it, targeting a 5 x 1 line within 1 square of them or a 3 cube within 10 squares of them. Each enemy in the area makes an Agility test. The rival chooses a damage type and a condition for the outcome of the test from one of the following pairs: sonic damage and [dazed](scc:mcdm.heroes.v1/condition/dazed), poison damage and [weakened](scc:mcdm.heroes.v1/condition/weakened), or fire damage and [frightened](scc:mcdm.heroes.v1/condition/frightened).
>
> - **≤11:** 11 damage; the condition affects the target (save ends)
> - **12-16:** 8 damage; the condition affects the target (EoT)
> - **17+:** 5 damage

> ⭐️ **Calling the Shots (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Each rival regains 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina). Until the end of the round, whenever a rival uses an ability against an enemy, each other rival [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to that enemy can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.

> ⭐️ **Coordinated Takedown (10 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Each rival moves up to their speed and uses a main action or maneuver that doesn't cost [Malice](scc:mcdm.monsters.v1/rule.monster/malice).
