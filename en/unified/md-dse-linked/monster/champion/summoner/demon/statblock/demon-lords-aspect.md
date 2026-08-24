---
agility: 5
cost: 9 essence for one champion
cost_amount: "9"
cost_resource: essence for one champion
file_basename: demon-lords-aspect
file_dpath: monster/champion/summoner/demon/statblock
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
free_strike_damage_type: Corruption
immunities:
    - Corruption 5
intuition: 2
item_id: demon-lords-aspect
item_name: Demon Lord's Aspect
keywords:
    - Abyssal
    - Demon
might: 2
movement: Teleport
name: Demon Lord's Aspect
organization: Champion
presence: 2
reason: 5
scc: mcdm.summoner.v1/monster.champion.summoner.demon.statblock/demon-lords-aspect
size: "2"
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: SPECIAL
type: statblock
weaknesses: []
---

```ds-sb
agility: 5
cost: 9 essence for one champion
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 5
      effects:
        - roll: 2d10 + 5
          tier1: 9 corruption [damage](../../../../../rule/damage/damage.md); [pull](../../../../../movement/forced-movement.md) 2
          tier2: 12 corruption [damage](../../../../../rule/damage/damage.md); [pull](../../../../../movement/forced-movement.md) 4
          tier3: 14 corruption [damage](../../../../../rule/damage/damage.md); [pull](../../../../../movement/forced-movement.md) 5
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Grasping Appendages
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: The Aspect's [free strikes](../../../../../feature/common/main-actions/free-strike.md) [teleport](../../../../../movement/teleport.md) the target 5 squares.
      feature_type: trait
      icon: ⭐️
      name: Warping Strike
      type: feature
    - effects:
        - effect: If the Aspect only targets one creature or object with a [strike](../../../../../rule/combat/strike.md), they deal additional [damage](../../../../../rule/damage/damage.md) to the target equal to your [Reason](../../../../../rule/character/reason.md).
      feature_type: trait
      icon: ⭐️
      name: Champion's Ire
      type: feature
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The Aspect takes [damage](../../../../../rule/damage/damage.md) from an enemy.
            **Effect:** The Aspect has a double [edge](../../../../../rule/dice/edge.md) on their next [power roll](../../../../../rule/dice/power-roll.md). They can choose to give this benefit to an ally within your Summoner's Range instead.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: I Like Your Taste
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: When the Aspect is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they make a [free strike](../../../../../feature/common/main-actions/free-strike.md) against each [adjacent](../../../../../rule/combat/adjacent.md) enemy before [dying](../../../../../rule/health/dying.md).
      feature_type: trait
      icon: ⭐️
      name: Frenzy
      type: feature
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
immunities:
    - Corruption 5
intuition: 2
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.champion.summoner.demon.statblock/demon-lords-aspect
    source: mcdm.summoner.v1
might: 2
movement: Teleport
name: Demon Lord's Aspect
organization: Champion
presence: 2
reason: 5
role: ""
size: "2"
speed: 5
stability: 2
stamina: SPECIAL
type: statblock
weaknesses: []
```
