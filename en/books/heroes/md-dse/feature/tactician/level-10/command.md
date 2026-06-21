---
action_type: feature
class: tactician
feature_type: feature
file_basename: command
file_dpath: feature/tactician/level-10
item_id: command
item_name: Command
level: "10"
name: Command
scc: mcdm.heroes.v1/feature.tactician.level-10/command
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You have an epic resource called command. Each time you finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite), you gain command equal to the [XP](scc.v1:mcdm.heroes.v1/rule.resource/experience) you gain. You can spend command on your abilities as if it were focus.

        Additionally, whenever you or any ally uses an ability to deal [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) to a creature marked by you, you can spend 1 command as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to increase the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) outcome for that target by one tier. Whenever an enemy marked by you makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll), you can spend 1 command as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to decrease the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) outcome by one tier.

        Command remains until you spend it.
feature_type: feature
metadata:
    class: tactician
    level: "10"
    name: Command
    scc: mcdm.heroes.v1/feature.tactician.level-10/command
    type: feature
name: Command
type: feature
```
