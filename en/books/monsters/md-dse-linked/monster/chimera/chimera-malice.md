---
features:
    - body: The chimera takes up a defensive stance. Until the start of their next turn, the chimera can make a [free strike](../../feature/common/main-actions/free-strike.md) against each enemy who comes within 2 squares of them.
      cost: 3 Malice
      icon: ⭐️
      name: Defensive Snapping
    - body: The chimera takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The chimera shakes the ground, causing an eruption of loose rocks and debris that creates three size 2 stone objects anywhere on the encounter map. Each creature [adjacent](../../rule/combat/adjacent.md) to one or more objects when they appear who has A < 2 takes 5 damage.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Unstable Terrain
    - body: Until the start of the chimera's next turn, all areas of the encounter map are shrouded in a thick cloud of ash. All creatures and objects on the map have [concealment](../../rule/combat/concealment.md) that the chimera ignores. Additionally, each enemy in the cloud who has I < 1 has [line of effect](../../rule/combat/line-of-effect.md) only within 3 squares. The [potency](../../rule/character/potency.md) of this feature increases by 1 each time it's used.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Ashen Clouds
file_basename: chimera-malice
file_dpath: monster/chimera
flavor: At the start of a chimera's turn, you can spend Malice to activate one of the following features.
item_id: chimera-malice
item_name: Chimera Malice
kind: malice
name: Chimera Malice
scc: mcdm.monsters.v1/monster.chimera/chimera-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The chimera takes up a defensive stance. Until the start of their next turn, the chimera can make a [free strike](../../feature/common/main-actions/free-strike.md) against each enemy who comes within 2 squares of them.
      cost: 3 Malice
      icon: ⭐️
      name: Defensive Snapping
    - body: The chimera takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The chimera shakes the ground, causing an eruption of loose rocks and debris that creates three size 2 stone objects anywhere on the encounter map. Each creature [adjacent](../../rule/combat/adjacent.md) to one or more objects when they appear who has A < 2 takes 5 damage.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Unstable Terrain
    - body: Until the start of the chimera's next turn, all areas of the encounter map are shrouded in a thick cloud of ash. All creatures and objects on the map have [concealment](../../rule/combat/concealment.md) that the chimera ignores. Additionally, each enemy in the cloud who has I < 1 has [line of effect](../../rule/combat/line-of-effect.md) only within 3 squares. The [potency](../../rule/character/potency.md) of this feature increases by 1 each time it's used.
      cost: 7 Malice
      icon: "\U0001F300"
      name: Ashen Clouds
flavor: At the start of a chimera's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.chimera/chimera-malice
    source: mcdm.monsters.v1
name: Chimera Malice
type: featureblock
```
