---
agility: 2
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: light-of-the-sun
file_dpath: monster/minion/summoner/elemental/statblock
flavor: These elementals are blazing white avian-shaped beings that are nearly impossible to perceive directly. Between a light of the sun's talons is a massive glowing sword that can split the heaviest of defenses asunder.
free_strike: 7
free_strike_damage_type: Fire
immunities:
    - Corruption R
    - fire R
intuition: 0
item_id: light-of-the-sun
item_name: Light of the Sun
keywords:
    - Elemental (Air)
    - Elemental (Green)
    - Elemental (Fire)
    - Elemental (Void)
might: 0
movement: Fly
name: Light of the Sun
organization: Minion
presence: 3
reason: 4
role: Support
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/light-of-the-sun
size: "2"
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: 17 | 17
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 7 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: 2d10 + R
          tier1: 7 fire [damage](../../../../../rule/damage/damage.md); I < WEAK [dazed](../../../../../condition/dazed.md) (EoT)
          tier2: 11 fire [damage](../../../../../rule/damage/damage.md); I < AVERAGE [dazed](../../../../../condition/dazed.md) (EoT)
          tier3: 16 fire [damage](../../../../../rule/damage/damage.md); I < STRONG [dazed](../../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Solar Blade
      target: One creature or object per minion
      type: feature
      usage: Main action
    - cost: 2 Essence
      effects:
        - effect: When the light is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), the area within 1 square of the light becomes wreathed in sentient flames until the end of the encounter. An enemy that enters this area or starts their [turn](../../../../../rule/combat/turn.md) there takes 3 fire [damage](../../../../../rule/damage/damage.md) and is [slowed](../../../../../condition/slowed.md) (EoT). You or any ally that enters this area or starts their [turn](../../../../../rule/combat/turn.md) there gains 5 [temporary Stamina](../../../../../rule/health/temporary-stamina.md) and their [speed](../../../../../rule/character/speed.md) increases by 2 until the end of their [turn](../../../../../rule/combat/turn.md).
      feature_type: trait
      icon: ⭐️
      name: Radiant Field
      type: feature
flavor: These elementals are blazing white avian-shaped beings that are nearly impossible to perceive directly. Between a light of the sun's talons is a massive glowing sword that can split the heaviest of defenses asunder.
free_strike: 7
immunities:
    - Corruption R
    - fire R
intuition: 0
keywords:
    - Elemental (Air)
    - Elemental (Green)
    - Elemental (Fire)
    - Elemental (Void)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/light-of-the-sun
    source: mcdm.summoner.v1
might: 0
movement: Fly
name: Light of the Sun
organization: Minion
presence: 3
reason: 4
role: Support
size: "2"
speed: 6
stability: 0
stamina: 17 | 17
type: statblock
weaknesses: []
```
