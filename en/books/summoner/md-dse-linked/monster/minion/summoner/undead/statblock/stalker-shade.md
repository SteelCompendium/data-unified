---
agility: 1
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: stalker-shade
file_dpath: monster/minion/summoner/undead/statblock
flavor: Shades are a form of umbral stalker that float free from any floor or surface. They can bend their appearance to completely vanish in the light.
free_strike: 5
immunities:
    - Corruption R
    - Poison R
intuition: 0
item_id: stalker-shade
item_name: Stalker Shade
keywords:
    - Undead
might: -2
movement: Fly, hover
name: Stalker Shade
organization: Minion
presence: 2
reason: 0
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/stalker-shade
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: 6 | 6
type: statblock
weaknesses: []
---

```ds-sb
agility: 1
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The stalker shade turns invisible, [shifts](../../../../../movement/shifting.md) 3 squares, and reappears after making a [strike](../../../../../rule/combat/strike.md).
      feature_type: trait
      icon: ⭐️
      name: Shadow Strike
      type: feature
    - effects:
        - effect: The stalker shade can move through other creatures and objects at normal speed. The first time in a round that the stalker shade passes through a creature, that creature takes 2 corruption damage. The stalker shade doesn't take damage from being [force moved](../../../../../movement/forced-movement.md) into objects.
      feature_type: trait
      icon: ⭐️
      name: Shadow Phasing
      type: feature
flavor: Shades are a form of umbral stalker that float free from any floor or surface. They can bend their appearance to completely vanish in the light.
free_strike: 5
immunities:
    - Corruption R
    - Poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/stalker-shade
    source: mcdm.summoner.v1
might: -2
movement: Fly, hover
name: Stalker Shade
organization: Minion
presence: 2
reason: 0
role: Ambusher
size: 1M
speed: 5
stability: 1
stamina: 6 | 6
type: statblock
weaknesses: []
```
