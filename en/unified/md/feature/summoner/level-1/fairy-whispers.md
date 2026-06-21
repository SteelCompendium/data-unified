---
class: summoner
feature_source: circle
level: "1"
name: Fairy Whispers
scc: mcdm.summoner.v1/feature.summoner.level-1/fairy-whispers
type: feature
---

Whenever you send a minion to perform a task for you outside of combat, they can bring back a rumor from the destination to which you sent them. When the minion returns, make a [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) [test](scc.v1:mcdm.heroes.v1/rule.test/test):

- **≤11:** You learn an undoubtedly false common rumor.
- **12-16:** You learn a common rumor that is most likely true.
- **17+:** You learn an obscure rumor that could either be true or false.

You gain a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the test for each subsequent rumor you collect either on the same day or in the same location.
