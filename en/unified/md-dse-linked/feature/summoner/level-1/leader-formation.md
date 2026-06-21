---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: leader-formation
file_dpath: feature/summoner/level-1
item_id: leader-formation
item_name: Leader Formation
level: "1"
name: Leader Formation
scc: mcdm.summoner.v1/feature.summoner.level-1/leader-formation
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You aren't affected by excess [damage](../../../rule/damage/damage.md) after all minions in a squad are dead. If your minion is within your Summoner's Range when they take [damage](../../../rule/damage/damage.md), you can choose to take damage in place of the minion.

        Additionally, you can use light armor [treasures](../../../rule/treasure/leveled-treasure.md) and light weapon [treasures](../../../rule/treasure/leveled-treasure.md) while you don't have a kit.

        <!-- @type: callout | @owner: loose -->
        > **Minions and Treasures**
        >
        > [Treasures](../../../rule/treasure/leveled-treasure.md) in Draw Steel are typically worded for you to use, which might create ambiguity for a [summoner](../../../class/summoner.md) managing an army. You can use the following guidelines to ensure the treasures you come across in your adventures do what they were intended to do.
        >
        > - Treasures that give you a [damage](../../../rule/damage/damage.md) bonus to [rolled damage](../../../rule/damage/rolled-damage.md) only apply to [power rolls](../../../rule/dice/power-roll.md) made from a non-minion's space. However, when you use [Strike for Me](../../ability/summoner/level-1/strike-for-me.md), any bonus damage is applied to each enemy and object that took damage.
        > - Once you reach level 4 as a [summoner](../../../class/summoner.md), you regain access to your normal [free strike](../../common/main-actions/free-strike.md) abilities while wielding a weapon treasure, an [implement](../../../rule/treasure/implement.md) treasure, or any treasure that enables you to make a [free strike](../../common/main-actions/free-strike.md) as a part of its effect.
        > - Treasures that increase the [distance](../../../rule/combat/distance.md) of ranged magic abilities also increase the distance of your Summoner's Range.
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "1"
    name: Leader Formation
    scc: mcdm.summoner.v1/feature.summoner.level-1/leader-formation
    type: feature
name: Leader Formation
type: feature
```
