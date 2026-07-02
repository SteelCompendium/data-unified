---
action_type: feature
class: summoner
feature_source: circle
feature_type: feature
file_basename: fairy-whispers
file_dpath: feature/summoner/level-1
item_id: fairy-whispers
item_name: Fairy Whispers
level: "1"
name: Fairy Whispers
scc: mcdm.summoner.v1/feature.summoner.level-1/fairy-whispers
source: mcdm.summoner.v1
subclass: spring
type: feature
---

```ds-feature
effects:
    - effect: |-
        Whenever you send a minion to perform a task for you outside of combat, they can bring back a rumor from the destination to which you sent them. When the minion returns, make a [Reason](../../../rule/character/reason.md) [test](../../../rule/test/test.md):

        - **≤11:** You learn an undoubtedly false common rumor.
        - **12-16:** You learn a common rumor that is most likely true.
        - **17+:** You learn an obscure rumor that could either be true or false.

        You gain a [bane](../../../rule/dice/bane.md) on the test for each subsequent rumor you collect either on the same day or in the same location.
feature_type: feature
metadata:
    class: summoner
    feature_source: circle
    level: "1"
    name: Fairy Whispers
    scc: mcdm.summoner.v1/feature.summoner.level-1/fairy-whispers
    subclass: spring
    type: feature
name: Fairy Whispers
type: feature
```
