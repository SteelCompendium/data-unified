---
agility: 2
cost: 9 essence for one champion
cost_amount: "9"
cost_resource: essence for one champion
file_basename: celestial-attendant
file_dpath: monster/champion/summoner/fey/statblock
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
free_strike_damage_type: Poison
immunities:
    - Damage 2
intuition: 2
item_id: celestial-attendant
item_name: Celestial Attendant
keywords:
    - Fey
might: 2
movement: Fly, hover
name: Celestial Attendant
organization: Champion
presence: 5
reason: 5
scc: mcdm.summoner.v1/monster.champion.summoner.fey.statblock/celestial-attendant
size: "2"
source: mcdm.summoner.v1
speed: 7
stability: 0
stamina: SPECIAL
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 9 essence for one champion
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: 2d10 + 5
          tier1: 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 14 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Pixie Swarm
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: A creature that takes [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) from the Attendant's [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) is I < AVERAGE unable to establish [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) beyond 3 squares ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)).
      feature_type: trait
      icon: ⭐️
      name: Neurotoxic Strike
      type: feature
    - effects:
        - effect: If the Attendant only targets one creature or object with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), they deal additional [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to the target equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason).
      feature_type: trait
      icon: ⭐️
      name: Champion's Ire
      type: feature
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The Attendant takes [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) from an enemy.
            **Effect:** The Attendant rings a bell, and you summon a signature minion into an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the Attendant.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Celestial Bell
      target: Self
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The Attendant starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) with [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to 2 × the number of fey minions within 1 square of them. This [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) lasts until the start of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      feature_type: trait
      icon: ⭐️
      name: Pixie Bouquet
      type: feature
    - effects:
        - effect: The Attendant is now size 3.
      feature_type: trait
      icon: ⭐️
      name: Size Increase
      type: feature
    - distance: 20 burst
      effects:
        - effect: |-
            **Champion Action**
            **Effect:** Each target gains 20 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) and receives the benefits of one of your [Flash Powder](scc.v1:mcdm.summoner.v1/feature.summoner.level-5/flash-powder) effects until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      feature_type: ability
      icon: ❗️
      keywords: []
      name: A Shower of Dust
      target: Self and each non-minion ally in the area
      type: feature
      usage: 1 Eidos
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
immunities:
    - Damage 2
intuition: 2
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.champion.summoner.fey.statblock/celestial-attendant
    source: mcdm.summoner.v1
might: 2
movement: Fly, hover
name: Celestial Attendant
organization: Champion
presence: 5
reason: 5
role: ""
size: "2"
speed: 7
stability: 0
stamina: SPECIAL
type: statblock
weaknesses: []
```
