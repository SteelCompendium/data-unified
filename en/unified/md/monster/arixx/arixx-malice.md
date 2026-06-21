---
features:
    - body: The arixx dribbles acid over their mandibles, causing the next strike they make to gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) and deal an extra 3 acid damage.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Burning Maw
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: The arixx's underground tunnels swell with pressure, causing a sudden influx of hot gas to burst from a 3-square-by-3-square area anywhere on the surface. Each enemy in the area makes an **[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) test**.
      name: Geyser
      power_roll:
        tiers:
            high: The target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) to the nearest unoccupied space outside the area.
            low: 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
            mid: 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    - body: The arixx takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The encounter map suddenly quakes, then begins to sink. Each creature on the ground who has A < 1 is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone). Until the end of the encounter, each creature who starts their turn on the ground and can't [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) must spend 1 additional square of movement to leave their starting position, or 2 squares if they start their turn [prone](scc.v1:mcdm.heroes.v1/condition/prone) or underground. A creature who starts and ends their turn in the same space on the ground and can't [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) sinks 1 square into the ground.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Earth Sink
flavor: At the start of an arixx's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Arixx Malice
scc: mcdm.monsters.v1/monster.arixx/arixx-malice
type: featureblock
---

At the start of an arixx's turn, you can spend Malice to activate one of the following features.

> 👤 **Burning Maw (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The arixx dribbles acid over their mandibles, causing the next strike they make to gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) and deal an extra 3 acid damage.

> 🔳 **Geyser (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The arixx's underground tunnels swell with pressure, causing a sudden influx of hot gas to burst from a 3-square-by-3-square area anywhere on the surface. Each enemy in the area makes an **[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) test**.
>
> - **≤11:** 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
> - **12-16:** 4 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** The target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) to the nearest unoccupied space outside the area.

> ☠️ **Solo Action (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The arixx takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🌀 **Earth Sink (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The encounter map suddenly quakes, then begins to sink. Each creature on the ground who has A < 1 is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone). Until the end of the encounter, each creature who starts their turn on the ground and can't [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) must spend 1 additional square of movement to leave their starting position, or 2 squares if they start their turn [prone](scc.v1:mcdm.heroes.v1/condition/prone) or underground. A creature who starts and ends their turn in the same space on the ground and can't [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) sinks 1 square into the ground.
