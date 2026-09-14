---
action_type: Main action
class: summoner
distance: 3 burst
effects:
    - effect: Each enemy minion in the area is permanently removed from the encounter map. Up to three non-leader or non-solo enemies in the area are removed from the encounter for 1 [round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round).
      name: Effect
    - effect: A leader or a solo enemy in the area that has R, I, or P < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)) as they are partially removed from the manifold. You can increase the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1 for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target you choose to sacrifice as a part of using this ability.
feature_source: summoner
feature_type: ability
file_basename: i-abjure-thee
file_dpath: feature/ability/summoner/level-9
flavor: Cast those not affixed to this manifold into the void of a minion's existence.
item_id: i-abjure-thee
item_name: I Abjure Thee
keywords:
    - Area
    - Magic
level: "9"
name: I Abjure Thee
scc: mcdm.summoner.v1/feature.ability.summoner.level-9/i-abjure-thee
source: mcdm.summoner.v1
target: Special
type: ability
---

```ds-feature
distance: 3 burst
effects:
    - effect: Each enemy minion in the area is permanently removed from the encounter map. Up to three non-leader or non-solo enemies in the area are removed from the encounter for 1 [round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round).
      name: Effect
    - effect: A leader or a solo enemy in the area that has R, I, or P < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)) as they are partially removed from the manifold. You can increase the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1 for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target you choose to sacrifice as a part of using this ability.
feature_type: ability
flavor: Cast those not affixed to this manifold into the void of a minion's existence.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: summoner
    distance: 3 burst
    effects:
        - effect: Each enemy minion in the area is permanently removed from the encounter map. Up to three non-leader or non-solo enemies in the area are removed from the encounter for 1 [round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round).
          name: Effect
        - effect: A leader or a solo enemy in the area that has R, I, or P < AVERAGE is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw)) as they are partially removed from the manifold. You can increase the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1 for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target you choose to sacrifice as a part of using this ability.
    feature_source: summoner
    flavor: Cast those not affixed to this manifold into the void of a minion's existence.
    keywords:
        - Area
        - Magic
    level: "9"
    name: I Abjure Thee
    scc: mcdm.summoner.v1/feature.ability.summoner.level-9/i-abjure-thee
    target: Special
    type: ability
name: I Abjure Thee
target: Special
type: feature
usage: Main action
```
