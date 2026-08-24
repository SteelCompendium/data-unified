---
agility: 2
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: knight-of-blood
file_dpath: monster/minion/summoner/elemental/statblock
flavor: These faceless suits of armor have visible rivers of deep red blood flowing throughout their being. Their blood has a powerful pull to it, causing any open wounds nearby to rip deeper and leak toward the knight.
free_strike: 7
free_strike_damage_type: Corruption
immunities:
    - Corruption R
intuition: 0
item_id: knight-of-blood
item_name: Knight of Blood
keywords:
    - Elemental (Earth)
    - Elemental (Fire)
    - Elemental (Rot)
    - Elemental (Water)
might: 4
movement: —
name: Knight of Blood
organization: Minion
presence: 3
reason: 0
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/knight-of-blood
size: 1L
source: mcdm.summoner.v1
speed: 6
stamina: 16 | 16
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 7 essence for two minions
ev: ""
features:
    - effects:
        - effect: The knight's melee [strikes](../../../../../rule/combat/strike.md) inflict P < STRONG [bleeding](../../../../../condition/bleeding.md) (save ends). While [bleeding](../../../../../condition/bleeding.md) this way, the target can't roll lower than a 3 on the die used to resolve [bleeding](../../../../../condition/bleeding.md) damage.
      feature_type: trait
      icon: ⭐️
      name: Scarlet Death
      type: feature
    - cost: 2 Essence
      effects:
        - effect: When the knight is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they move up to their [speed](../../../../../rule/character/speed.md) ignoring [opportunity attacks](../../../../../rule/combat/opportunity-attack.md). Each square that they exit during this movement pools with blood until the end of the encounter. Each affected square is considered [difficult terrain](../../../../../movement/difficult-terrain.md) for enemies and deals 3 corruption [damage](../../../../../rule/damage/damage.md) to an enemy when they first enter it on a [turn](../../../../../rule/combat/turn.md). Whenever a [bleeding](../../../../../condition/bleeding.md) enemy starts their [turn](../../../../../rule/combat/turn.md) within 10 squares of the blood pool, they are pulled 2 toward the nearest affected square, ignoring [stability](../../../../../rule/character/stability.md).
      feature_type: trait
      icon: ⭐️
      name: Red River
      type: feature
flavor: These faceless suits of armor have visible rivers of deep red blood flowing throughout their being. Their blood has a powerful pull to it, causing any open wounds nearby to rip deeper and leak toward the knight.
free_strike: 7
immunities:
    - Corruption R
intuition: 0
keywords:
    - Elemental (Earth)
    - Elemental (Fire)
    - Elemental (Rot)
    - Elemental (Water)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/knight-of-blood
    source: mcdm.summoner.v1
might: 4
movement: —
name: Knight of Blood
organization: Minion
presence: 3
reason: 0
role: Controller
size: 1L
speed: 6
stability: 0
stamina: 16 | 16
type: statblock
weaknesses: []
```
