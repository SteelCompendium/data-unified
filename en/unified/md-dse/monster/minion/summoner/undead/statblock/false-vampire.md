---
agility: 1
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: false-vampire
file_dpath: monster/minion/summoner/undead/statblock
flavor: A false vampire is a bestial, bipedal ghoul that draws life from liquified remains. In death, their hands curl into thick hooks, their bodies turn a putrid red-green as if wearing a dress suit, and their mouth twists and extends into a large feeding needle that can pierce steel.
free_strike: 8
immunities:
    - Corruption R
    - poison R
intuition: 0
item_id: false-vampire
item_name: False Vampire
keywords:
    - Undead
might: 4
movement: Climb
name: False Vampire
organization: Minion
presence: 0
reason: 3
role: Brute
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/false-vampire
size: 1L
source: mcdm.summoner.v1
speed: 6
stability: 2
stamina: 17 | 17
type: statblock
weaknesses: []
---

```ds-sb
agility: 1
cost: 7 essence for two minions
ev: ""
features:
    - effects:
        - effect: The false vampire's melee [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) have a distance of 2 and inflict M < AVERAGE [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT). The false vampire can move the target while they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way. At the start of a [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) creature's [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they take acid [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason).
      feature_type: trait
      icon: ⭐️
      name: Proboscis Strike
      type: feature
    - effects:
        - effect: The false vampire has a [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) of 10 while a creature is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) within 10.
      feature_type: trait
      icon: ⭐️
      name: Bloodthirsty
      type: feature
flavor: A false vampire is a bestial, bipedal ghoul that draws life from liquified remains. In death, their hands curl into thick hooks, their bodies turn a putrid red-green as if wearing a dress suit, and their mouth twists and extends into a large feeding needle that can pierce steel.
free_strike: 8
immunities:
    - Corruption R
    - poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/false-vampire
    source: mcdm.summoner.v1
might: 4
movement: Climb
name: False Vampire
organization: Minion
presence: 0
reason: 3
role: Brute
size: 1L
speed: 6
stability: 2
stamina: 17 | 17
type: statblock
weaknesses: []
```
