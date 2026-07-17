---
agility: 3
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: sprite-olyender
file_dpath: monster/minion/summoner/fey/statblock
flavor: These brawny sprites wear heavy beetle armor and have a halo hovering away from their backs where their wings used to be. The faster the halo spins, the more power the olyender generates, enabling them to stand toe to toe with giants.
free_strike: 8
immunities: []
intuition: 1
item_id: sprite-olyender
item_name: Sprite Olyender
keywords:
    - Fey
might: 4
movement: Fly
name: Sprite Olyender
organization: Minion
presence: 2
reason: 0
role: Brute
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-olyender
size: 1T
source: mcdm.summoner.v1
speed: 6
stamina: 17 | 17
type: statblock
weaknesses: []
---

```ds-sb
agility: 3
cost: 7 essence for two minions
ev: ""
features:
    - effects:
        - effect: The olyender's melee [strikes](../../../../../rule/combat/strike.md) inflict [push](../../../../../movement/forced-movement.md) 4. If the target is [force moved](../../../../../movement/forced-movement.md) into an object, they are M < AVERAGE knocked [prone](../../../../../condition/prone.md) and can't stand (save ends).
      feature_type: trait
      icon: ⭐️
      name: Warrior's Toss
      type: feature
    - effects:
        - effect: When targeting a creature with a [grab](../../../../../feature/common/maneuvers/grab.md) or [forced movement](../../../../../movement/forced-movement.md), the olyender's [size](../../../../../rule/character/size.md) is considered one larger than the target.
      feature_type: trait
      icon: ⭐️
      name: Use Their Might
      type: feature
    - effects:
        - effect: The olyender has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: These brawny sprites wear heavy beetle armor and have a halo hovering away from their backs where their wings used to be. The faster the halo spins, the more power the olyender generates, enabling them to stand toe to toe with giants.
free_strike: 8
immunities: []
intuition: 1
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-olyender
    source: mcdm.summoner.v1
might: 4
movement: Fly
name: Sprite Olyender
organization: Minion
presence: 2
reason: 0
role: Brute
size: 1T
speed: 6
stability: 0
stamina: 17 | 17
type: statblock
weaknesses: []
```
