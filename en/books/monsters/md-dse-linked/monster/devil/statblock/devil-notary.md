---
agility: 1
ev: 7 for four minions
file_basename: devil-notary
file_dpath: monster/devil/statblock
free_strike: 3
immunities:
    - Fire 5
intuition: 1
item_id: devil-notary
item_name: Devil Notary
keywords:
    - Devil
    - Infernal
level: 5
might: 0
name: Devil Notary
organization: Minion
presence: 2
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.devil.statblock/devil-notary
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "8"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 1
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 3 fire damage
          tier2: 5 fire damage; R < 2 the target takes a [bane](../../../rule/dice/bane.md) on their next strike
          tier3: 6 fire damage; R < 3 the target takes a [bane](../../../rule/dice/bane.md) on their next strike
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Importunity
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If a creature within 10 squares speaks the notary's true name, the notary loses their fire immunity and any nondamaging effects of their [signature ability](../../../rule/combat/signature-ability.md) until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 3
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.devil.statblock/devil-notary
    source: mcdm.monsters.v1
might: 0
name: Devil Notary
organization: Minion
presence: 2
reason: 3
role: Hexer
size: 1M
speed: 6
stability: 0
stamina: "8"
type: statblock
with_captain: +5 bonus to ranged distance
```
