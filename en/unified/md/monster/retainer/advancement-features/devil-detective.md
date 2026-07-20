---
features:
    - cost: Encounter
      distance: 4 cube within 5
      icon: "\U0001F3F9"
      keywords:
        - Area
        - Magic
      level: 4
      name: Soul Sleuth
      power_roll:
        formula: 2d10 + highest characteristic
        tiers:
            high: 5 damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
            low: 2 damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
            mid: 4 damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      sections:
        - label: Special
          text: The detective can instantly kill one or more of their minions to give themself a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
        - label: Effect
          text: Any enemy that was hiding in the area is revealed. The area is now [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
      target: Each enemy or object in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      level: 4
      name: Summon Violents
      sections:
        - label: Effect
          text: The detective summons 3 violents into unoccupied spaces within distance. On each of the detective's turns, they direct the squad of **violents** to move and use a main action.
      target: Special
      usage: Main action
    - cost: Encounter
      distance: 5 burst
      icon: "\U0001F300"
      keywords:
        - Area
        - Magic
      level: 7
      name: Cleansing Flense
      sections:
        - label: Effect
          text: Each target moves up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) toward an ally. Each ally within [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) of the detective can give one [EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn) or save ends effect they're affected by to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) minion and end that effect on themself.
      target: Each of the detective's minions in the area
      trailing: Until the end of the encounter, whenever an enemy kills a target and has P < STRONG, they receive all EoT or save ends effects the target was affected by.
      usage: Maneuver
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Area
        - Magic
      level: 10
      name: Blightwash
      power_roll:
        formula: 2d10 + highest characteristic
        tiers:
            high: 10 corruption damage; M < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
            low: 5 corruption damage; M < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
            mid: 8 corruption damage; M < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      sections:
        - label: Effect
          text: The minion explodes. Make a power roll, targeting each enemy within 2 squares of the target.
      target: One of the detective's minions
      trailing: The area within 2 squares of the exploded minion is covered in blight until the end of the encounter. Abilities used against an enemy in the area have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      level: 10
      name: Summon Gorrres
      sections:
        - label: Effect
          text: The detective summons two gorrres into unoccupied spaces within distance. On each of the detective's turns, they direct the squad of **gorrres** to move and use a main action.
      target: Special
      usage: Main action
name: Devil Detective Advancement Features
scc: mcdm.summoner.v1/monster.retainer.advancement-features/devil-detective
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🏹 **Soul Sleuth 2d10 + highest characteristic (Encounter)**
>
> | **Area, Magic** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|----------------:|
> | **📏 4 cube within 5** | **🎯 Each enemy or object in the area** |
>
> **Special:** The detective can instantly kill one or more of their minions to give themself a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
>
> 2 damage; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> 4 damage; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> 5 damage; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** Any enemy that was hiding in the area is revealed. The area is now [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.

> 🏹 **Summon Violents (Encounter)**
>
> | **Magic, Ranged** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|----------------:|
> | **📏 Ranged 10** | **🎯 Special** |
>
> **Effect:** The detective summons 3 violents into unoccupied spaces within distance. On each of the detective's turns, they direct the squad of **violents** to move and use a main action.

> **Level 7 Retainer Advancement Ability**

> 🌀 **Cleansing Flense (Encounter)**
>
> | **Area, Magic** | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|-------------:|
> | **📏 5 burst** | **🎯 Each of the detective's minions in the area** |
>
> **Effect:** Each target moves up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) toward an ally. Each ally within [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) of the detective can give one [EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn) or save ends effect they're affected by to an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) minion and end that effect on themself.
>
> Until the end of the encounter, whenever an enemy kills a target and has P < STRONG, they receive all EoT or save ends effects the target was affected by.

> **Level 10 Retainer Advancement Ability**

> 🏹 **Blightwash 2d10 + highest characteristic (Encounter)**
>
> | **Area, Magic** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|----------------:|
> | **📏 Ranged 5** | **🎯 One of the detective's minions** |
>
> **Effect:** The minion explodes. Make a power roll, targeting each enemy within 2 squares of the target.
>
> 5 corruption damage; M < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> 8 corruption damage; M < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> 10 corruption damage; M < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> The area within 2 squares of the exploded minion is covered in blight until the end of the encounter. Abilities used against an enemy in the area have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).

> 🏹 **Summon Gorrres (Encounter)**
>
> | **Magic, Ranged** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|----------------:|
> | **📏 Ranged 10** | **🎯 Special** |
>
> **Effect:** The detective summons two gorrres into unoccupied spaces within distance. On each of the detective's turns, they direct the squad of **gorrres** to move and use a main action.
