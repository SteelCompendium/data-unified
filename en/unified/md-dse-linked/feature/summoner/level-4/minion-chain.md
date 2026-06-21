---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: minion-chain
file_dpath: feature/summoner/level-4
item_id: minion-chain
item_name: Minion Chain
level: "4"
name: Minion Chain
scc: mcdm.summoner.v1/feature.summoner.level-4/minion-chain
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Whenever you use [Minion Bridge](../../ability/summoner/level-1/minion-bridge.md) as a maneuver, each of your [minions](../level-1/minions.md) within your Summoner's Range can [shift](../../../movement/shifting.md) up to their [speed](../../../rule/character/speed.md) before the maneuver takes effect, as long as each [minion](../level-1/minions.md) that [shifts](../../../movement/shifting.md) ends their movement [adjacent](../../../rule/combat/adjacent.md) to another one of your [minions](../level-1/minions.md).

        Additionally, your [minions](../level-1/minions.md) can chain themselves together to function as a ladder or a swinging rope. When your [minions](../level-1/minions.md) move as a part of using [Minion Bridge](../../ability/summoner/level-1/minion-bridge.md), each [minion](../level-1/minions.md) can use this movement to [shift](../../../movement/shifting.md) into a position directly beneath another one of your [minions](../level-1/minions.md), hoisting them and each other [minion](../level-1/minions.md) they have hoisted, until they form a chain. The chain can then choose to fall across an unoccupied space and/or the topmost [minion](../level-1/minions.md) [grabs](../../common/maneuvers/grab.md) an object to keep the chain steady.

        The chain lasts until the start of your next [turn](../../../rule/combat/turn.md) or until the chain is no longer steady. The chain can also end when a [minion](../level-1/minions.md) in the chain is destroyed or when you command your [minions](../level-1/minions.md) to let go as a [free maneuver](../../../rule/combat/free-maneuver.md). All [size](../../../rule/character/size.md) 1 [minions](../level-1/minions.md) count as one square when determining the chain's length.
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "4"
    name: Minion Chain
    scc: mcdm.summoner.v1/feature.summoner.level-4/minion-chain
    type: feature
name: Minion Chain
type: feature
```
