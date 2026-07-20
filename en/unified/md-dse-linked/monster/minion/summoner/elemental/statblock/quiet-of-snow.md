---
agility: 2
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: quiet-of-snow
file_dpath: monster/minion/summoner/elemental/statblock
flavor: This elemental is a pure-white vulpine with six legs that freely sprints through the air. Their howls are telepathic, washing over the receivers with a strong chill and a wave of goosebumps.
free_strike: 4
free_strike_damage_type: Cold
immunities:
    - Sonic R
    - Cold R
intuition: 0
item_id: quiet-of-snow
item_name: Quiet of Snow
keywords:
    - Elemental (Air)
    - Elemental (Rot)
    - Elemental (Water)
might: -1
movement: Fly, hover
name: Quiet of Snow
organization: Minion
presence: 3
reason: 0
role: Artillery
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/quiet-of-snow
size: 1S
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 5 essence for three minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: 2d10 + R
          tier1: 4 cold [damage](../../../../../rule/damage/damage.md); M < WEAK [slowed](../../../../../condition/slowed.md) (EoT)
          tier2: 6 cold [damage](../../../../../rule/damage/damage.md); M < AVERAGE [slowed](../../../../../condition/slowed.md) (EoT)
          tier3: 8 cold [damage](../../../../../rule/damage/damage.md); M < STRONG speed is 0 (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Freezing Howl
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the quiet is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they launch a refreshing blast of air into an area equal to their [size](../../../../../rule/character/size.md) + 1 within 5 before being destroyed. Each ally in the affected area gains a [surge](../../../../../rule/resource/surge.md).
      feature_type: trait
      icon: ⭐️
      name: Cold Surge
      type: feature
flavor: This elemental is a pure-white vulpine with six legs that freely sprints through the air. Their howls are telepathic, washing over the receivers with a strong chill and a wave of goosebumps.
free_strike: 4
immunities:
    - Sonic R
    - Cold R
intuition: 0
keywords:
    - Elemental (Air)
    - Elemental (Rot)
    - Elemental (Water)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/quiet-of-snow
    source: mcdm.summoner.v1
might: -1
movement: Fly, hover
name: Quiet of Snow
organization: Minion
presence: 3
reason: 0
role: Artillery
size: 1S
speed: 5
stability: 1
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
```
