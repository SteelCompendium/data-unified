---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: husk
file_dpath: monster/minion/summoner/undead/statblock
flavor: Husks have stiff corpses that snap and crackle with each sudden movement. Corrosive breath endlessly billows from their slackjawed faces.
free_strike: 1
immunities:
    - Damage 2
    - Corruption R
    - Poison R
intuition: -1
item_id: husk
item_name: Husk
keywords:
    - Undead
might: 2
movement: —
name: Husk
organization: Minion
presence: -1
reason: -1
role: Defender
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/husk
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: "3"
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: The husk's melee [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) inflict M < WEAK [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)). The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1 for each additional husk adjacent to the target (maximum +2).
      feature_type: trait
      icon: ⭐️
      name: Rotting Strike
      type: feature
flavor: Husks have stiff corpses that snap and crackle with each sudden movement. Corrosive breath endlessly billows from their slackjawed faces.
free_strike: 1
immunities:
    - Damage 2
    - Corruption R
    - Poison R
intuition: -1
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/husk
    source: mcdm.summoner.v1
might: 2
movement: —
name: Husk
organization: Minion
presence: -1
reason: -1
role: Defender
size: 1M
speed: 5
stability: 1
stamina: "3"
type: statblock
weaknesses: []
```
