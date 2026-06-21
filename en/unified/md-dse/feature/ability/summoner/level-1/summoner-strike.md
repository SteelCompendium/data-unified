---
action_type: Main action
class: summoner
distance: Melee 1 or Ranged 5
effect: R [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If the target has R < WEAK, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
feature_source: summoner
feature_type: ability
file_basename: summoner-strike
file_dpath: feature/ability/summoner/level-1
flavor: A sudden burst of energy erupts from your implement and shocks your foes' nerves.
item_id: summoner-strike
item_name: Summoner Strike
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
level: "1"
name: Summoner Strike
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/summoner-strike
source: mcdm.summoner.v1
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1 or Ranged 5
effects:
    - effect: R [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If the target has R < WEAK, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
feature_type: ability
flavor: A sudden burst of energy erupts from your implement and shocks your foes' nerves.
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: summoner
    distance: Melee 1 or Ranged 5
    effect: R [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage). If the target has R < WEAK, they are [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
    feature_source: summoner
    flavor: A sudden burst of energy erupts from your implement and shocks your foes' nerves.
    keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
    level: "1"
    name: Summoner Strike
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/summoner-strike
    target: One creature or object
    type: ability
name: Summoner Strike
target: One creature or object
type: feature
usage: Main action
```
