---
agility: 1
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: false-vampire
file_dpath: monster/minion/summoner/undead/statblock
flavor: A false vampire is a bestial, bipedal ghoul that draws life from liquified remains. In death, their hands curl into thick hooks, their bodies turn a putrid red-green as if wearing a dress suit, and their mouth twists and extends into a large feeding needle that can pierce steel.
free_strike: 8
free_strike_damage_type: Acid
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
        - effect: The false vampire's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) have a distance of 2 and inflict M < AVERAGE [restrained](../../../../../condition/restrained.md) (EoT). The false vampire can move the target while they are [restrained](../../../../../condition/restrained.md) this way. At the start of a [restrained](../../../../../condition/restrained.md) creature's [turn](../../../../../rule/combat/turn.md), they take acid [damage](../../../../../rule/damage/damage.md) equal to your [Reason](../../../../../rule/character/reason.md).
      feature_type: trait
      icon: ⭐️
      name: Proboscis Strike
      type: feature
    - effects:
        - effect: The false vampire has a [speed](../../../../../rule/character/speed.md) of 10 while a creature is [bleeding](../../../../../condition/bleeding.md) within 10.
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
