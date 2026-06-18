---
features:
    - cost: 3 Malice
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Iron Jaws
      usage: Maneuver
    - icon: '|'
      name: "\U0001F4CF 1 cube within 3**   | **\U0001F3AF Special"
      power_roll:
        tiers:
            high: No effect.
            low: 6 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
            mid: 4 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
      sections:
        - label: Effect
          text: A gnoll acting this turn drops an iron-jawed snare into the area. The first time any enemy moves into the area, they make an **Agility test**. If they were unaware of the snare, the test takes a bane.
        - label: Effect
          text: While an enemy is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, each gnoll in the encounter gains an edge on strikes made against them.
    - body: One gnoll [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) suddenly explodes into a pool of blood, splattering the area within 3 squares of them. Any gnoll who starts their turn in this area deals an extra 5 damage on their next strike before the end of their turn. Once per round, an abyssal hyena who starts their turn in the area turns into a **gnoll marauder**, keeping their current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      cost: 5 Malice
      icon: "\U0001F464"
      name: Bloodpool
    - body: Until the end of the encounter, the encounter map is encased in a soundscape of laughter and howling. Each enemy takes a bane on the first power roll they make each round. Whenever a gnoll is killed, this effect is suppressed until the start of the next round.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Echoes of Laughter
flavor: At the start of any gnoll's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Gnoll Malice
scc: mcdm.monsters.v1/monster.gnoll/gnoll-malice
type: featureblock
---

At the start of any gnoll's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 🔳 **Iron Jaws (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Ranged, Weapon** |   **Maneuver** |
> |--------------------------|---------------:|
> | **📏 1 cube within 3**   | **🎯 Special** 
>
> **Effect:** A gnoll acting this turn drops an iron-jawed snare into the area. The first time any enemy moves into the area, they make an **Agility test**. If they were unaware of the snare, the test takes a bane.
>
> - **≤11:** 6 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 4 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
> - **17+:** No effect.
>
> **Effect:** While an enemy is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, each gnoll in the encounter gains an edge on strikes made against them.

> 👤 **Bloodpool (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> One gnoll [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) suddenly explodes into a pool of blood, splattering the area within 3 squares of them. Any gnoll who starts their turn in this area deals an extra 5 damage on their next strike before the end of their turn. Once per round, an abyssal hyena who starts their turn in the area turns into a **gnoll marauder**, keeping their current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> 🌀 **Echoes of Laughter (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the encounter, the encounter map is encased in a soundscape of laughter and howling. Each enemy takes a bane on the first power roll they make each round. Whenever a gnoll is killed, this effect is suppressed until the start of the next round.
