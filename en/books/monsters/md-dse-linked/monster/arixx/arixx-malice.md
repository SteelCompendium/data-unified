---
features:
    - body: The arixx dribbles acid over their mandibles, causing the next strike they make to gain an [edge](../../rule/dice/edge.md) and deal an extra 3 acid damage.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Burning Maw
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: The arixx's underground tunnels swell with pressure, causing a sudden influx of hot gas to burst from a 3-square-by-3-square area anywhere on the surface. Each enemy in the area makes an **[Agility](../../rule/character/agility.md) test**.
      name: Geyser
      power_roll:
        tiers:
            high: The target [shifts](../../movement/shifting.md) to the nearest unoccupied space outside the area.
            low: 4 damage; vertical [push](../../movement/forced-movement.md) 5
            mid: 4 damage; vertical [push](../../movement/forced-movement.md) 3
    - body: The arixx takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The encounter map suddenly quakes, then begins to sink. Each creature on the ground who has A < 1 is knocked [prone](../../condition/prone.md). Until the end of the encounter, each creature who starts their turn on the ground and can't [burrow](../../movement/burrow.md) must spend 1 additional square of movement to leave their starting position, or 2 squares if they start their turn [prone](../../condition/prone.md) or underground. A creature who starts and ends their turn in the same space on the ground and can't [burrow](../../movement/burrow.md) sinks 1 square into the ground.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Earth Sink
file_basename: arixx-malice
file_dpath: monster/arixx
flavor: At the start of an arixx's turn, you can spend Malice to activate one of the following features.
item_id: arixx-malice
item_name: Arixx Malice
kind: malice
name: Arixx Malice
scc: mcdm.monsters.v1/monster.arixx/arixx-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The arixx dribbles acid over their mandibles, causing the next strike they make to gain an [edge](../../rule/dice/edge.md) and deal an extra 3 acid damage.
      cost: 3 Malice
      icon: "\U0001F464"
      name: Burning Maw
    - cost: 5 Malice
      icon: "\U0001F533"
      intro: The arixx's underground tunnels swell with pressure, causing a sudden influx of hot gas to burst from a 3-square-by-3-square area anywhere on the surface. Each enemy in the area makes an **[Agility](../../rule/character/agility.md) test**.
      name: Geyser
      power_roll:
        tiers:
            high: The target [shifts](../../movement/shifting.md) to the nearest unoccupied space outside the area.
            low: 4 damage; vertical [push](../../movement/forced-movement.md) 5
            mid: 4 damage; vertical [push](../../movement/forced-movement.md) 3
    - body: The arixx takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The encounter map suddenly quakes, then begins to sink. Each creature on the ground who has A < 1 is knocked [prone](../../condition/prone.md). Until the end of the encounter, each creature who starts their turn on the ground and can't [burrow](../../movement/burrow.md) must spend 1 additional square of movement to leave their starting position, or 2 squares if they start their turn [prone](../../condition/prone.md) or underground. A creature who starts and ends their turn in the same space on the ground and can't [burrow](../../movement/burrow.md) sinks 1 square into the ground.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Earth Sink
flavor: At the start of an arixx's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.arixx/arixx-malice
    source: mcdm.monsters.v1
name: Arixx Malice
type: featureblock
```
