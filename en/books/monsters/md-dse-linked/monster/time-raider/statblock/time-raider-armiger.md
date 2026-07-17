---
agility: 2
ev: "10"
file_basename: time-raider-armiger
file_dpath: monster/time-raider/statblock
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
item_id: time-raider-armiger
item_name: Time Raider Armiger
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 0
name: Time Raider Armiger
organization: Platoon
presence: 0
reason: 2
role: Defender
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-armiger
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "60"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 10 damage
          tier3: 13 damage; R < 2 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Serrated Saber
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 20
      effects:
        - roll: Power Roll + 2
          tier1: 4 psychic damage; R < 0 5 poison damage
          tier2: 6 psychic damage; R < 1 5 poison damage
          tier3: 9 psychic damage; R < 2 5 poison damage
      feature_type: ability
      icon: ❗️
      keywords:
        - Psionic
        - Ranged
      name: Shared Sickness
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: The armiger doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
    - effects:
        - effect: Any time raider who starts their turn with [line of effect](../../../rule/combat/line-of-effect.md) to the armiger can end one condition affecting the.
      feature_type: trait
      icon: ⭐️
      name: Kuran'zoi Heraldry
      type: feature
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-armiger
    source: mcdm.monsters.v1
might: 0
name: Time Raider Armiger
organization: Platoon
presence: 0
reason: 2
role: Defender
size: 1M
speed: 5
stability: 0
stamina: "60"
type: statblock
```
