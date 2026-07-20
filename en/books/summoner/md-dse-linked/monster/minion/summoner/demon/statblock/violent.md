---
agility: 3
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: violent
file_dpath: monster/minion/summoner/demon/statblock
flavor: The violents are lanky, oily bipeds with bright red flesh that contort and snap their bodies into unassuming objects. Their mimicry is particularly precise, to the point where it's unclear whether their victims die from the surprise or the violent transformation process first.
free_strike: 4
free_strike_damage_type: Corruption
immunities: []
intuition: -1
item_id: violent
item_name: Violent
keywords:
    - Abyssal
    - Demon
might: 2
movement: Climb
name: Violent
organization: Minion
presence: -1
reason: 0
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/violent
size: 1M
source: mcdm.summoner.v1
speed: 7
stability: 1
stamina: 5 | 5 | 5
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 3
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The violent's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) deal an additional 2 [damage](../../../../../rule/damage/damage.md) to each [adjacent](../../../../../rule/combat/adjacent.md) enemy from whom they were hidden. The violent loses their disguise after striking.
      feature_type: trait
      icon: ⭐️
      name: Transforming Strike
      type: feature
    - effects:
        - effect: The violent uses the [Hide](../../../../../feature/common/maneuvers/hide.md) maneuver at the start of their [turn](../../../../../rule/combat/turn.md) as a [free maneuver](../../../../../rule/combat/free-maneuver.md), disguising themselves as a a [size](../../../../../rule/character/size.md) 1M or smaller object.
      feature_type: trait
      icon: ⭐️
      name: Mimicry
      type: feature
    - effects:
        - effect: Each creature [adjacent](../../../../../rule/combat/adjacent.md) to the violent can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: The violents are lanky, oily bipeds with bright red flesh that contort and snap their bodies into unassuming objects. Their mimicry is particularly precise, to the point where it's unclear whether their victims die from the surprise or the violent transformation process first.
free_strike: 4
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/violent
    source: mcdm.summoner.v1
might: 2
movement: Climb
name: Violent
organization: Minion
presence: -1
reason: 0
role: Ambusher
size: 1M
speed: 7
stability: 1
stamina: 5 | 5 | 5
type: statblock
weaknesses:
    - Holy 1
```
