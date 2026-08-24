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
          tier1: 9 corruption [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 12 corruption [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier3: 14 corruption [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
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
        - effect: The Aspect's [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target 5 squares.
      feature_type: trait
      icon: ⭐️
      name: Warping Strike
      type: feature
    - effects:
        - effect: If the Aspect only targets one creature or object with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal additional [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to the target equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason).
      feature_type: trait
      icon: ⭐️
      name: Champion's Ire
      type: feature
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The Aspect takes [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) from an enemy.
            **Effect:** The Aspect has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll). They can choose to give this benefit to an ally within your Summoner's Range instead.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: I Like Your Taste
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: When the Aspect is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy before [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
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
