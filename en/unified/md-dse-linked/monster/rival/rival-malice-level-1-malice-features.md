---
features:
    - body: Until the end of the round, each rival can impose a bane on a [strike](../../rule/combat/strike.md) made against an [adjacent](../../rule/combat/adjacent.md) rival as a free triggered action.
      cost: 3 Malice
      icon: ⭐️
      name: Work as One
    - body: Until the end of the round, whenever any rival makes a power roll against the target of their Rivalry trait, they roll a d3 and add it to the power roll.
      cost: 3 Malice
      icon: ⭐️
      name: We Just Do It Better
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: 'One rival pulls out a magic consumable and hurls it, targeting a 5 x 1 line within 1 square of them or a 3 cube within 10 squares of them. Each enemy in the area makes an Agility test. The rival chooses a damage type and a condition for the outcome of the test from one of the following pairs: sonic damage and [dazed](../../condition/dazed.md), poison damage and [weakened](../../condition/weakened.md), or fire damage and [frightened](../../condition/frightened.md).'
      name: Check Out Our Loot
      power_roll:
        tiers:
            high: 5 damage
            low: 11 damage; the condition affects the target (save ends)
            mid: 8 damage; the condition affects the target (EoT)
    - body: Each rival regains 10 [Stamina](../../rule/health/stamina.md). Until the end of the round, whenever a rival uses an ability against an enemy, each other rival [adjacent](../../rule/combat/adjacent.md) to that enemy can make a [free strike](../../feature/common/main-actions/free-strike.md) against them.
      cost: 7 Malice
      icon: ⭐️
      name: Calling the Shots
    - body: Each rival moves up to their speed and uses a main action or maneuver that doesn't cost [Malice](../../rule/monster/malice.md).
      cost: 10 Malice
      icon: ⭐️
      name: Coordinated Takedown
file_basename: rival-malice-level-1-malice-features
file_dpath: monster/rival
flavor: At the start of any rival's turn, you can spend Malice to activate one of the following features.
item_id: rival-malice-level-1-malice-features
item_name: Rival Malice (Level 1+ Malice Features)
kind: malice
level: 1
name: Rival Malice (Level 1+ Malice Features)
scc: mcdm.monsters.v1/monster.rival/rival-malice-level-1-malice-features
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Until the end of the round, each rival can impose a bane on a [strike](../../rule/combat/strike.md) made against an [adjacent](../../rule/combat/adjacent.md) rival as a free triggered action.
      cost: 3 Malice
      icon: ⭐️
      name: Work as One
    - body: Until the end of the round, whenever any rival makes a power roll against the target of their Rivalry trait, they roll a d3 and add it to the power roll.
      cost: 3 Malice
      icon: ⭐️
      name: We Just Do It Better
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: 'One rival pulls out a magic consumable and hurls it, targeting a 5 x 1 line within 1 square of them or a 3 cube within 10 squares of them. Each enemy in the area makes an Agility test. The rival chooses a damage type and a condition for the outcome of the test from one of the following pairs: sonic damage and [dazed](../../condition/dazed.md), poison damage and [weakened](../../condition/weakened.md), or fire damage and [frightened](../../condition/frightened.md).'
      name: Check Out Our Loot
      power_roll:
        tiers:
            high: 5 damage
            low: 11 damage; the condition affects the target (save ends)
            mid: 8 damage; the condition affects the target (EoT)
    - body: Each rival regains 10 [Stamina](../../rule/health/stamina.md). Until the end of the round, whenever a rival uses an ability against an enemy, each other rival [adjacent](../../rule/combat/adjacent.md) to that enemy can make a [free strike](../../feature/common/main-actions/free-strike.md) against them.
      cost: 7 Malice
      icon: ⭐️
      name: Calling the Shots
    - body: Each rival moves up to their speed and uses a main action or maneuver that doesn't cost [Malice](../../rule/monster/malice.md).
      cost: 10 Malice
      icon: ⭐️
      name: Coordinated Takedown
flavor: At the start of any rival's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.rival/rival-malice-level-1-malice-features
    source: mcdm.monsters.v1
name: Rival Malice (Level 1+ Malice Features)
type: featureblock
```
