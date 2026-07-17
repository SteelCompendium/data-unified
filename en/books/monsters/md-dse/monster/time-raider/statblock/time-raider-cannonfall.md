---
agility: 2
ev: "10"
file_basename: time-raider-cannonfall
file_dpath: monster/time-raider/statblock
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
item_id: time-raider-cannonfall
item_name: Time Raider Cannonfall
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 0
name: Time Raider Cannonfall
organization: Platoon
presence: 0
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-cannonfall
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: 4 sonic damage
          tier2: 7 sonic damage
          tier3: 10 sonic damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
        - Weapon
      name: Sunderbuss
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: 5 burst
      effects:
        - effect: |-
            **Trigger:** A creature damages the cannonfall with a ranged or area ability.
            **Effect:** The damage is halved for the cannonfall and each target also affected by the triggering ability.
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
        - Psionic
      name: Buss Buffe
      target: Self and each ally in the area
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The cannonfall doesn't take a bane on strikes against creatures with concealment or cover.
      feature_type: trait
      icon: ⭐️
      name: Foresight Squared
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
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-cannonfall
    source: mcdm.monsters.v1
might: 0
name: Time Raider Cannonfall
organization: Platoon
presence: 0
reason: 2
role: Artillery
size: 1L
speed: 5
stability: 3
stamina: "40"
type: statblock
```
