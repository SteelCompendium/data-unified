---
action_type: Main action
class: summoner
distance: Melee 3
effect: This [strike](../../../../rule/combat/strike.md) deals an additional 2 [damage](../../../../rule/damage/damage.md) for each ally [adjacent](../../../../rule/combat/adjacent.md) to you.
feature_source: summoner
feature_type: ability
file_basename: summoners-sword
file_dpath: feature/ability/summoner/level-1
flavor: You draw your strength from the army you surround yourself with and summon a hot blade of energy and fervor.
item_id: summoners-sword
item_name: Summoner's Sword
keywords:
    - Magic
    - Melee
    - Strike
level: "1"
name: Summoner's Sword
power_roll_characteristic: Reason
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/summoners-sword
source: mcdm.summoner.v1
target: One creature or object
tier1: R damage
tier2: 2 + R damage
tier3: 4 + R damage
type: ability
---

```ds-feature
distance: Melee 3
effects:
    - effect: This [strike](../../../../rule/combat/strike.md) deals an additional 2 [damage](../../../../rule/damage/damage.md) for each ally [adjacent](../../../../rule/combat/adjacent.md) to you.
    - roll: Power Roll + Reason
      tier1: R damage
      tier2: 2 + R damage
      tier3: 4 + R damage
feature_type: ability
flavor: You draw your strength from the army you surround yourself with and summon a hot blade of energy and fervor.
keywords:
    - Magic
    - Melee
    - Strike
metadata:
    action_type: Main action
    class: summoner
    distance: Melee 3
    effect: This [strike](../../../../rule/combat/strike.md) deals an additional 2 [damage](../../../../rule/damage/damage.md) for each ally [adjacent](../../../../rule/combat/adjacent.md) to you.
    feature_source: summoner
    flavor: You draw your strength from the army you surround yourself with and summon a hot blade of energy and fervor.
    keywords:
        - Magic
        - Melee
        - Strike
    level: "1"
    name: Summoner's Sword
    power_roll_characteristic: Reason
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/summoners-sword
    target: One creature or object
    tier1: R damage
    tier2: 2 + R damage
    tier3: 4 + R damage
    type: ability
name: Summoner's Sword
target: One creature or object
type: feature
usage: Main action
```
