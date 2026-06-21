---
class: summoner
feature_source: summoner
level: "1"
name: Quick Command
scc: mcdm.summoner.v1/feature.summoner.level-1/quick-command
type: feature
---

You have a special command you can issue to your minions. Choose one of the following quick commands. You can change your quick command along with your formation (see [Formation](formation.md)) by performing intense study as a [respite](../../../rule/resource/respite.md) activity. (*Quick Build:* [Shield!](../../ability/summoner/level-1/shield.md))

## Focus Fire! {data-scc="mcdm.summoner.v1/feature.summoner.level-1/focus-fire"}

You have the following triggered action.

## Focus Fire! {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/focus-fire"}

*You ensure the enemy can't escape the incoming attack.*

| **—** | **Triggered** |
|-------|-------------:|
| **📏 Summoner's Range** | **🎯 Self or one ally** |

**Trigger:** The target deals [damage](../../../rule/damage/damage.md) to another creature.

**Effect:** The target gains a [surge](../../../rule/resource/surge.md) for each of your minions [adjacent](../../../rule/combat/adjacent.md) to them (up to a maximum of 3 surges), which they can use on the triggering damage.

**Spend 1 Essence:** If the triggering damage is from an ability that uses a [power roll](../../../rule/dice/power-roll.md), the [power roll](../../../rule/dice/power-roll.md) gains an [edge](../../../rule/dice/edge.md).

## Halt! {data-scc="mcdm.summoner.v1/feature.summoner.level-1/halt"}

You have the following triggered action.

## Halt! {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/halt"}

*You order a minion to get in the way.*

| **—** | **Triggered** |
|-------|-------------:|
| **📏 Summoner's Range** | **🎯 One creature** |

**Trigger:** The target starts their [turn](../../../rule/combat/turn.md), moves, or is [force moved](../../../movement/forced-movement.md).

**Effect:** You summon a signature minion in an unoccupied space [adjacent](../../../rule/combat/adjacent.md) to the target. If the target is [force moved](../../../movement/forced-movement.md) into the minion, you can choose to make the target take no [damage](../../../rule/damage/damage.md) from the collision.

**Special:** Instead of summoning a new minion, you can command one of your minions within [distance](../../../rule/combat/distance.md) to [shift](../../../movement/shifting.md) up to their [speed](../../../rule/character/speed.md) toward a square [adjacent](../../../rule/combat/adjacent.md) to the target before any additional effects occur.

## Not Yet! {data-scc="mcdm.summoner.v1/feature.summoner.level-1/not-yet"}

You have the following triggered action.

## Not Yet! {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/not-yet" data-cost="3 Essence"}

*I command you to not die.*

| **—** | **Triggered** |
|-------|-------------:|
| **📏 Summoner's Range** | **🎯 One ally** |

**Trigger:** The target receives enough damage to die or be destroyed.

**Special:** If the target is a minion, they must be the only minion remaining in their squad.

**Effect:** The [damage](../../../rule/damage/damage.md) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](../../../rule/health/stamina.md).

## Shield! {data-scc="mcdm.summoner.v1/feature.summoner.level-1/shield"}

You have the following triggered action.

## Shield! {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/shield"}

*You call upon a minion to use their body to dampen the blow.*

| **—** | **Triggered** |
|-------|-------------:|
| **📏 Summoner's Range** | **🎯 Self or one ally** |

**Trigger:** The target is targeted by a [strike](../../../rule/combat/strike.md).

**Effect:** If one of your minions is [adjacent](../../../rule/combat/adjacent.md) to the target and is within [distance](../../../rule/combat/distance.md) of the strike, they become the new target of the strike.

**Spend 1 Essence:** Instead of commanding an existing minion, you summon a signature minion into an unoccupied space [adjacent](../../../rule/combat/adjacent.md) to the target to take the strike.
