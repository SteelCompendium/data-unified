---
action_type: Main action
class: summoner
distance: Melee 1 or Ranged 5
effects:
    - effect: R [damage](../../../../rule/damage/damage.md). If the target has R < WEAK, they are [slowed](../../../../condition/slowed.md) (save ends).
      name: Effect
    - effect: This ability has the Charge keyword when it's used as a melee [strike](../../../../rule/combat/strike.md).
      name: Special
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
    - effect: R [damage](../../../../rule/damage/damage.md). If the target has R < WEAK, they are [slowed](../../../../condition/slowed.md) (save ends).
      name: Effect
    - effect: This ability has the Charge keyword when it's used as a melee [strike](../../../../rule/combat/strike.md).
      name: Special
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
    effects:
        - effect: R [damage](../../../../rule/damage/damage.md). If the target has R < WEAK, they are [slowed](../../../../condition/slowed.md) (save ends).
          name: Effect
        - effect: This ability has the Charge keyword when it's used as a melee [strike](../../../../rule/combat/strike.md).
          name: Special
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
