---
action_type: feature
class: censor
feature_type: feature
file_basename: implement-of-wrath
file_dpath: feature/censor/level-6
item_id: implement-of-wrath
item_name: Implement of Wrath
level: "6"
name: Implement of Wrath
scc: mcdm.heroes.v1/feature.censor.level-6/implement-of-wrath
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Each time you finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite), you can choose one hero's weapon, including your own, to channel [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) power as an [implement](scc.v1:mcdm.heroes.v1/rule.treasure/implement) of your god's wrath. The weapon becomes magic and gains the following benefits until your next [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite):

        - Strikes with the weapon deal extra holy damage equal to the wielder's highest [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score.
        - Any creature struck by the weapon who has holy weakness and has P < STRONG is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
        - Any minion targeted by a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) using the weapon dies. That minion's [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) maximum is removed from the minion [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) pool before any damage is applied to the rest of the squad.
        - The weapon's wielder can't be made [frightened](scc.v1:mcdm.heroes.v1/condition/frightened).
feature_type: feature
metadata:
    class: censor
    level: "6"
    name: Implement of Wrath
    scc: mcdm.heroes.v1/feature.censor.level-6/implement-of-wrath
    type: feature
name: Implement of Wrath
type: feature
```
