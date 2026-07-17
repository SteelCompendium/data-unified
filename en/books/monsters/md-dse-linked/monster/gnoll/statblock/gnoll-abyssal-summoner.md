---
agility: 0
ev: "4"
file_basename: gnoll-abyssal-summoner
file_dpath: monster/gnoll/statblock
free_strike: 2
intuition: 2
item_id: gnoll-abyssal-summoner
item_name: Gnoll Abyssal Summoner
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 1
name: Gnoll Abyssal Summoner
organization: Horde
presence: 2
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-abyssal-summoner
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "20"
type: statblock
---

```ds-sb
agility: 0
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 4 fire damage
          tier2: 5 fire damage
          tier3: 7 fire damage; I < 2 the target is burning (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Flame Wad
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - effect: '**Effect:** Two abyssal hyenas claw up from the ground in unoccupied spaces within distance.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Call Abyssal Hyenas
      target: Special
      type: feature
      usage: Maneuver
    - cost: 4 Malice
      distance: 2 burst
      effects:
        - effect: '**Effect:** One abyssal hyena target turns into a gnoll marauder, keeping their current [Stamina](../../../rule/health/stamina.md). If any target hasn''t used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Summoner's Cackletongue
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever a non-[minion](../../../rule/organization/minion.md) ally within 5 squares of the abyssal summoner is reduced to 0 [Stamina](../../../rule/health/stamina.md), the abyssal summoner moves up to their speed and can make a melee [free strike](../../../feature/common/main-actions/free-strike.md).
      feature_type: trait
      icon: ⭐️
      name: Death Frenzy
      type: feature
free_strike: 2
intuition: 2
keywords:
    - Abyssal
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-abyssal-summoner
    source: mcdm.monsters.v1
might: 1
name: Gnoll Abyssal Summoner
organization: Horde
presence: 2
reason: 0
role: Support
size: 1M
speed: 5
stability: 1
stamina: "20"
type: statblock
```
