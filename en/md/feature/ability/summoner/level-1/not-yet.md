---
action_type: Triggered
class: summoner
distance: Summoner's Range
effect: The [damage](scc:mcdm.heroes.v1/rule.damage/damage) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
flavor: I command you to not die.
keywords:
    - —
level: "1"
name: Not Yet!
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/not-yet
target: One ally
trigger: The target receives enough damage to die or be destroyed.
type: ability
---

*I command you to not die.*

| **—** | **Triggered** |
|-------|-------------:|
| **📏 Summoner's Range** | **🎯 One ally** |

**Trigger:** The target receives enough damage to die or be destroyed.

**Special:** If the target is a minion, they must be the only minion remaining in their squad.

**Effect:** The [damage](scc:mcdm.heroes.v1/rule.damage/damage) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
