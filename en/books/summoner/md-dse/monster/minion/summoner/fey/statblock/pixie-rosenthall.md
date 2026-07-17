---
agility: 2
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: pixie-rosenthall
file_dpath: monster/minion/summoner/fey/statblock
flavor: The collective of blood-eyed pixie warriors that make up a rosenthall are also known as rosies. It's said that some rosenthall armies contain thousands of pixies and can span half the length of a wode.
free_strike: 3
immunities: []
intuition: 0
item_id: pixie-rosenthall
item_name: Pixie Rosenthall
keywords:
    - Fey
    - Swarm
might: 0
movement: Fly, hover
name: Pixie Rosenthall
organization: Minion
presence: 3
reason: 4
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-rosenthall
size: "2"
source: mcdm.summoner.v1
speed: 6
stability: 1
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 5 essence for three minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: 2d10 + R
          tier1: 3 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); pull 2; A < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
          tier2: 6 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); pull 3; A < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
          tier3: 8 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); pull 4; A < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Stickerbush Symphony
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The rosenthall can move through squares as if they were [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1T, and can occupy other creatures' spaces. At the start of the rosenthall's [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they deal 2 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to each enemy whose space they share.
      feature_type: trait
      icon: ⭐️
      name: Swarm
      type: feature
flavor: The collective of blood-eyed pixie warriors that make up a rosenthall are also known as rosies. It's said that some rosenthall armies contain thousands of pixies and can span half the length of a wode.
free_strike: 3
immunities: []
intuition: 0
keywords:
    - Fey
    - Swarm
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-rosenthall
    source: mcdm.summoner.v1
might: 0
movement: Fly, hover
name: Pixie Rosenthall
organization: Minion
presence: 3
reason: 4
role: Harrier
size: "2"
speed: 6
stability: 1
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
```
