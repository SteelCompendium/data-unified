---
action_type: Free triggered
class: summoner
distance: Summoner's Range
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Up to three targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
      tier2: Up to five targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
      tier3: Up to seven targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
    - effect: On a [natural 19 or 20](scc.v1:mcdm.heroes.v1/rule.dice/natural-19-20), each target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      name: Special
    - effect: Your minions act in place of you making a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or using a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability). If you were granted the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) against a specific target, your minions must strike the same target. If the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) granted you a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability), you have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_source: summoner
feature_type: ability
file_basename: strike-for-me
file_dpath: feature/ability/summoner/level-1
flavor: Your minions fight in your stead.
item_id: strike-for-me
item_name: Strike for Me
keywords:
    - Magic
    - Ranged
level: "1"
name: Strike for Me
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/strike-for-me
source: mcdm.summoner.v1
target: Each of your minions
tier1: Up to three targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
tier2: Up to five targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
tier3: Up to seven targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
trigger: You use a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability).
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: Up to three targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
      tier2: Up to five targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
      tier3: Up to seven targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
    - effect: On a [natural 19 or 20](scc.v1:mcdm.heroes.v1/rule.dice/natural-19-20), each target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      name: Special
    - effect: Your minions act in place of you making a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or using a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability). If you were granted the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) against a specific target, your minions must strike the same target. If the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) granted you a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability), you have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
feature_type: ability
flavor: Your minions fight in your stead.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Free triggered
    class: summoner
    distance: Summoner's Range
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: Up to three targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
          tier2: Up to five targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
          tier3: Up to seven targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
        - effect: On a [natural 19 or 20](scc.v1:mcdm.heroes.v1/rule.dice/natural-19-20), each target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
          name: Special
        - effect: Your minions act in place of you making a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or using a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability). If you were granted the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) against a specific target, your minions must strike the same target. If the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) granted you a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability), you have an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
          name: Effect
    feature_source: summoner
    flavor: Your minions fight in your stead.
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Strike for Me
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/strike-for-me
    target: Each of your minions
    tier1: Up to three targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
    tier2: Up to five targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
    tier3: Up to seven targets each make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
    trigger: You use a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability).
    type: ability
name: Strike for Me
target: Each of your minions
trigger: You use a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability).
type: feature
usage: Free triggered
```
