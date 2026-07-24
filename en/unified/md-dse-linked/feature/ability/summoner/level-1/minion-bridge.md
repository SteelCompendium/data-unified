---
action_type: Maneuver
class: summoner
distance: Melee 1
effects:
    - effect: You [shift](../../../../movement/shifting.md) into a square adjacent to the target, including vertically.
      name: Effect
    - effect: An adjacent ally can [shift](../../../../movement/shifting.md) alongside you during this movement. They must end their movement in an unoccupied square adjacent to the last minion you moved through.
      name: 1 Essence
feature_source: summoner
feature_type: ability
file_basename: minion-bridge
file_dpath: feature/ability/summoner/level-1
flavor: Your minions do everything in their power to form a safe path for you to cross.
item_id: minion-bridge
item_name: Minion Bridge
keywords:
    - Magic
level: "1"
name: Minion Bridge
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/minion-bridge
source: mcdm.summoner.v1
target: One of your minions
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You [shift](../../../../movement/shifting.md) into a square adjacent to the target, including vertically.
      name: Effect
    - effect: An adjacent ally can [shift](../../../../movement/shifting.md) alongside you during this movement. They must end their movement in an unoccupied square adjacent to the last minion you moved through.
      name: 1 Essence
feature_type: ability
flavor: Your minions do everything in their power to form a safe path for you to cross.
keywords:
    - Magic
metadata:
    action_type: Maneuver
    class: summoner
    distance: Melee 1
    effects:
        - effect: You [shift](../../../../movement/shifting.md) into a square adjacent to the target, including vertically.
          name: Effect
        - effect: An adjacent ally can [shift](../../../../movement/shifting.md) alongside you during this movement. They must end their movement in an unoccupied square adjacent to the last minion you moved through.
          name: 1 Essence
    feature_source: summoner
    flavor: Your minions do everything in their power to form a safe path for you to cross.
    keywords:
        - Magic
    level: "1"
    name: Minion Bridge
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/minion-bridge
    target: One of your minions
    type: ability
name: Minion Bridge
target: One of your minions
type: feature
usage: Maneuver
```
