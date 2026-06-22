---
action_type: feature
class: censor
feature_type: feature
file_basename: word-of-death-deferred
file_dpath: feature/censor/level-7
item_id: word-of-death-deferred
item_name: Word of Death Deferred
level: "7"
name: Word of Death Deferred
scc: mcdm.heroes.v1/feature.censor.level-7/word-of-death-deferred
source: mcdm.heroes.v1
subclass: death
type: feature
---

```ds-feature
effects:
    - effect: |-
        You can stop death from taking your allies. When an ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) of your [My Life for Yours](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours) ability dies and you are not [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to instead have that ally fall unconscious until they regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

        Additionally, your abilities deal an extra 5 damage to [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) creatures.
feature_type: feature
metadata:
    class: censor
    level: "7"
    name: Word of Death Deferred
    scc: mcdm.heroes.v1/feature.censor.level-7/word-of-death-deferred
    subclass: death
    type: feature
name: Word of Death Deferred
type: feature
```
