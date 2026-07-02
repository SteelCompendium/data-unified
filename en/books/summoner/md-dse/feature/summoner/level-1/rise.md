---
action_type: feature
class: summoner
feature_source: circle
feature_type: feature
file_basename: rise
file_dpath: feature/summoner/level-1
item_id: rise
item_name: Rise!
level: "1"
name: Rise!
scc: mcdm.summoner.v1/feature.summoner.level-1/rise
source: mcdm.summoner.v1
subclass: graves
type: feature
---

```ds-feature
effects:
    - effect: |-
        Once per [round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round), when a creature dies unwillingly within your Summoner's Range, you can use a [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to summon a signature undead minion in their space at no cost, even if you're at your minion maximum, but only if they can be organized into one of your squads. The new minion can't act until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).

        This ability becomes a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) if the target was a minion (either yours or an enemy).
feature_type: feature
metadata:
    class: summoner
    feature_source: circle
    level: "1"
    name: Rise!
    scc: mcdm.summoner.v1/feature.summoner.level-1/rise
    subclass: graves
    type: feature
name: Rise!
type: feature
```
