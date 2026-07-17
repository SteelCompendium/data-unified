---
agility: 2
cost: 9 essence for one champion
cost_amount: "9"
cost_resource: essence for one champion
file_basename: dragons-portent
file_dpath: monster/champion/summoner/elemental/statblock
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
immunities:
    - Affinity 5
intuition: 5
item_id: dragons-portent
item_name: Dragon's Portent
keywords:
    - Dragon
    - Elemental
might: 2
movement: Fly
name: Dragon's Portent
organization: Champion
presence: 2
reason: 5
scc: mcdm.summoner.v1/monster.champion.summoner.elemental.statblock/dragons-portent
size: "2"
source: mcdm.summoner.v1
speed: 6
stability: 4
stamina: SPECIAL
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 9 essence for one champion
ev: ""
features:
    - effects:
        - effect: 'The Portent selects an affinity for one of the following [damage types](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) when they are summoned: acid, cold, corruption, fire, lightning, or poison. This type determines the Portent''s affinity [immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) and the [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) of their abilities.'
      feature_type: trait
      icon: ⭐️
      name: Affinity
      type: feature
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: 2d10 + 5
          tier1: 9 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 12 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
          tier3: 14 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Elemental Tail Swing
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: The Portent's [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) inflict M < STRONG [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)). While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 1d6 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) at the start of each of their [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      feature_type: trait
      icon: ⭐️
      name: Sealing Strike
      type: feature
    - effects:
        - effect: If the Portent only targets one creature or object with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal additional [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to the target equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason).
      feature_type: trait
      icon: ⭐️
      name: Champion's Ire
      type: feature
    - effects:
        - effect: Whenever an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature deals [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to the Portent, they take 4 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage).
      feature_type: trait
      icon: ⭐️
      name: Searing Wyrmscale
      type: feature
    - effects:
        - effect: Once per [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the Portent can take 10 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to allow you or an ally within your Summoner's Range to gain 1 [heroic resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource). This [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) can't be reduced in any way.
      feature_type: trait
      icon: ⭐️
      name: Dragon Heart
      type: feature
    - effects:
        - effect: The Portent is now size 3.
      feature_type: trait
      icon: ⭐️
      name: Size Increase
      type: feature
    - distance: 4 cube within 10
      effects:
        - effect: |-
            **Champion Action**
            **Effect:** 9 affinity [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). The [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) ignores [immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity). The affected area becomes [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). An enemy has affinity [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 while occupying an affected square.
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
        - Magic
        - Ranged
      name: A Breath Felt in a Hurricane
      target: Each enemy and object in the area
      type: feature
      usage: 1 Eidos
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
immunities:
    - Affinity 5
intuition: 5
keywords:
    - Dragon
    - Elemental
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.champion.summoner.elemental.statblock/dragons-portent
    source: mcdm.summoner.v1
might: 2
movement: Fly
name: Dragon's Portent
organization: Champion
presence: 2
reason: 5
role: ""
size: "2"
speed: 6
stability: 4
stamina: SPECIAL
type: statblock
weaknesses: []
```
