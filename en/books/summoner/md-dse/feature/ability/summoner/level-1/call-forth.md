---
action_type: Main action
class: summoner
distance: Summoner's Range
effects:
    - effect: 'You summon one or more minions from your [portfolio](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/portfolio) into unoccupied spaces within distance. Choose one of the following options:'
      name: Effect
    - effect: You summon one [signature minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) for each essence you spend on this ability.
      name: Signature Minions
    - effect: You summon the set number of minions listed on the stat block for their essence cost.
      name: All Other Minions
feature_source: summoner
feature_type: ability
file_basename: call-forth
file_dpath: feature/ability/summoner/level-1
flavor: My power is yours, and yours, mine. I summon thee.
item_id: call-forth
item_name: Call Forth (1+ Essence)
keywords:
    - Magic
    - Ranged
level: "1"
name: Call Forth (1+ Essence)
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/call-forth
source: mcdm.summoner.v1
target: Self
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: 'You summon one or more minions from your [portfolio](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/portfolio) into unoccupied spaces within distance. Choose one of the following options:'
      name: Effect
    - effect: You summon one [signature minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) for each essence you spend on this ability.
      name: Signature Minions
    - effect: You summon the set number of minions listed on the stat block for their essence cost.
      name: All Other Minions
feature_type: ability
flavor: My power is yours, and yours, mine. I summon thee.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: summoner
    distance: Summoner's Range
    effects:
        - effect: 'You summon one or more minions from your [portfolio](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/portfolio) into unoccupied spaces within distance. Choose one of the following options:'
          name: Effect
        - effect: You summon one [signature minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) for each essence you spend on this ability.
          name: Signature Minions
        - effect: You summon the set number of minions listed on the stat block for their essence cost.
          name: All Other Minions
    feature_source: summoner
    flavor: My power is yours, and yours, mine. I summon thee.
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Call Forth (1+ Essence)
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/call-forth
    target: Self
    type: ability
name: Call Forth (1+ Essence)
target: Self
type: feature
usage: Main action
```
