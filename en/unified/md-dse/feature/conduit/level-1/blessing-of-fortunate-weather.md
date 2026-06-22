---
action_type: feature
class: conduit
feature_type: feature
file_basename: blessing-of-fortunate-weather
file_dpath: feature/conduit/level-1
item_id: blessing-of-fortunate-weather
item_name: Blessing of Fortunate Weather
level: "1"
name: Blessing of Fortunate Weather
scc: mcdm.heroes.v1/feature.conduit.level-1/blessing-of-fortunate-weather
source: mcdm.heroes.v1
subclass: storm
type: feature
---

```ds-feature
effects:
    - effect: |-
        Each time you finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite), you can decide the weather conditions within 100 squares. Until you finish another [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite), the weather conditions you establish follow you through any mundane outdoor locations. Choose one of the following types of weather, each of which grants a benefit to you and your allies:

        **Clear:** You and your allies gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on [tests](scc.v1:mcdm.heroes.v1/rule.test/test) that use the Search or Navigate skills.

        **Foggy:** You and your allies gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on [tests](scc.v1:mcdm.heroes.v1/rule.test/test) that use the Hide skill. **Overcast:** You and your allies gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on [tests](scc.v1:mcdm.heroes.v1/rule.test/test) that use the [Endurance](scc.v1:mcdm.heroes.v1/skill.exploration/endurance) skill.

        **Precipitation:** When the ground is muddy or snowy, you and your allies gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on [tests](scc.v1:mcdm.heroes.v1/rule.test/test) that use the [Track](scc.v1:mcdm.heroes.v1/skill.intrigue/track) skill.

        If you are in the same area as a creature using this or a similar feature who has chosen a different weather effect, the features negate each other where their areas overlap.
feature_type: feature
metadata:
    class: conduit
    level: "1"
    name: Blessing of Fortunate Weather
    scc: mcdm.heroes.v1/feature.conduit.level-1/blessing-of-fortunate-weather
    subclass: storm
    type: feature
name: Blessing of Fortunate Weather
type: feature
```
