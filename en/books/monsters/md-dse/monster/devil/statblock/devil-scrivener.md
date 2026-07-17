---
agility: 3
ev: 7 for four minions
file_basename: devil-scrivener
file_dpath: monster/devil/statblock
free_strike: 3
immunities:
    - Fire 5
intuition: 1
item_id: devil-scrivener
item_name: Devil Scrivener
keywords:
    - Devil
    - Infernal
level: 5
might: 0
movement: Fly
name: Devil Scrivener
organization: Minion
presence: 2
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.devil.statblock/devil-scrivener
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "9"
type: statblock
with_captain: +3 bonus to speed
---

```ds-sb
agility: 3
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 corruption damage
          tier2: 5 corruption damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
          tier3: 6 corruption damage; [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Magic
        - Melee
        - Strike
      name: Litigation
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If a creature within 10 squares speaks the scrivener's true name, the scrivener loses their fire immunity and any nondamaging effects of their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) until the end of the encounter.
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
    scc: mcdm.monsters.v1/monster.devil.statblock/devil-scrivener
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: Devil Scrivener
organization: Minion
presence: 2
reason: 1
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "9"
type: statblock
with_captain: +3 bonus to speed
```
