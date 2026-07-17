---
features:
    - body: The bugbear activates a Malice Feature available to goblins.
      cost: 3-7 Malice
      icon: ⭐️
      name: Goblin Malice Features
    - body: For every 3 [Malice](../../rule/monster/malice.md) spent, one non-[minion](../../rule/organization/minion.md) bugbear acting this turn grabs an iron ball and can use a maneuver to throw it at a creature within 5 squares of them. The creature takes damage equal to 8 - the number of squares the iron ball was thrown, and if they have M < 1, they are [slowed](../../condition/slowed.md) (save ends).
      cost: 3+ Malice
      icon: "\U0001F464"
      name: Grab Iron Ball
    - body: For every 5 [Malice](../../rule/monster/malice.md) spent, one non-[minion](../../rule/organization/minion.md) bugbear acting this turn grabs a javelin and can use a maneuver to throw it at a creature within 5 squares of them. The creature takes damage equal to 12 - the number of squares the javelin was thrown, and if they have M < 1, they are [bleeding](../../condition/bleeding.md) (save ends). While a creature is [bleeding](../../condition/bleeding.md) this way, any ally of the bugbear within 2 squares of them can use a free maneuver to [pull](../../movement/forced-movement.md) the [bleeding](../../condition/bleeding.md) creature up to 2 squares.
      cost: 5+ Malice
      icon: "\U0001F464"
      name: Grab Javelin
    - body: A bugbear infuses the encounter map with bu'gathic magic. Until the end of the encounter, all bugbears and allies have their speed doubled and can automatically climb at full speed while moving. Additionally, if the target of any bugbear or ally's strike has I < 1, the target is also [frightened](../../condition/frightened.md) (save ends) and must move their speed in a straight line away from the creature who made the strike.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Show Them the Great Fear
file_basename: bugbear-malice
file_dpath: monster/bugbear
flavor: At the start of any bugbear's turn, you can spend Malice to activate one of the following features.
item_id: bugbear-malice
item_name: Bugbear Malice
kind: malice
name: Bugbear Malice
scc: mcdm.monsters.v1/monster.bugbear/bugbear-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The bugbear activates a Malice Feature available to goblins.
      cost: 3-7 Malice
      icon: ⭐️
      name: Goblin Malice Features
    - body: For every 3 [Malice](../../rule/monster/malice.md) spent, one non-[minion](../../rule/organization/minion.md) bugbear acting this turn grabs an iron ball and can use a maneuver to throw it at a creature within 5 squares of them. The creature takes damage equal to 8 - the number of squares the iron ball was thrown, and if they have M < 1, they are [slowed](../../condition/slowed.md) (save ends).
      cost: 3+ Malice
      icon: "\U0001F464"
      name: Grab Iron Ball
    - body: For every 5 [Malice](../../rule/monster/malice.md) spent, one non-[minion](../../rule/organization/minion.md) bugbear acting this turn grabs a javelin and can use a maneuver to throw it at a creature within 5 squares of them. The creature takes damage equal to 12 - the number of squares the javelin was thrown, and if they have M < 1, they are [bleeding](../../condition/bleeding.md) (save ends). While a creature is [bleeding](../../condition/bleeding.md) this way, any ally of the bugbear within 2 squares of them can use a free maneuver to [pull](../../movement/forced-movement.md) the [bleeding](../../condition/bleeding.md) creature up to 2 squares.
      cost: 5+ Malice
      icon: "\U0001F464"
      name: Grab Javelin
    - body: A bugbear infuses the encounter map with bu'gathic magic. Until the end of the encounter, all bugbears and allies have their speed doubled and can automatically climb at full speed while moving. Additionally, if the target of any bugbear or ally's strike has I < 1, the target is also [frightened](../../condition/frightened.md) (save ends) and must move their speed in a straight line away from the creature who made the strike.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Show Them the Great Fear
flavor: At the start of any bugbear's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.bugbear/bugbear-malice
    source: mcdm.monsters.v1
name: Bugbear Malice
type: featureblock
```
