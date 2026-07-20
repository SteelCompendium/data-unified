---
agility: 1
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: twisted-bengrul
file_dpath: monster/minion/summoner/demon/statblock
flavor: The bengrul is an undulating heap of glass and flesh. They shatter pieces of themselves to disrupt senses and inflict grisly wounds on their prey.
free_strike: 4
free_strike_damage_type: Psychic
immunities: []
intuition: -1
item_id: twisted-bengrul
item_name: Twisted Bengrul
keywords:
    - Abyssal
    - Demon
might: 2
movement: —
name: Twisted Bengrul
organization: Minion
presence: 0
reason: -1
role: Hexer
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/twisted-bengrul
size: 1L
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: 5 | 5
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 1
cost: 3 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: 2d10 + R
          tier1: 4 damage; P < WEAK twisted (save ends)
          tier2: 6 damage; P < AVERAGE twisted (save ends)
          tier3: 8 damage; P < STRONG twisted (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Mind Twist
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Each creature adjacent to the ensnarer can't be [hidden](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: The bengrul is an undulating heap of glass and flesh. They shatter pieces of themselves to disrupt senses and inflict grisly wounds on their prey.
free_strike: 4
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/twisted-bengrul
    source: mcdm.summoner.v1
might: 2
movement: —
name: Twisted Bengrul
organization: Minion
presence: 0
reason: -1
role: Hexer
size: 1L
speed: 5
stability: 1
stamina: 5 | 5
type: statblock
weaknesses:
    - Holy 1
```
