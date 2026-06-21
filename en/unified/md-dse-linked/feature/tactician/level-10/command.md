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
        You have an epic resource called command. Each time you finish a [respite](../../../rule/resource/respite.md), you gain command equal to the [XP](../../../rule/resource/experience.md) you gain. You can spend command on your abilities as if it were focus.

        Additionally, whenever you or any ally uses an ability to deal [rolled damage](../../../rule/damage/rolled-damage.md) to a creature marked by you, you can spend 1 command as a free [triggered action](../../../rule/combat/triggered-action.md) to increase the [power roll](../../../rule/dice/power-roll.md) outcome for that target by one tier. Whenever an enemy marked by you makes an [ability roll](../../../rule/dice/ability-roll.md), you can spend 1 command as a free [triggered action](../../../rule/combat/triggered-action.md) to decrease the [power roll](../../../rule/dice/power-roll.md) outcome by one tier.

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
