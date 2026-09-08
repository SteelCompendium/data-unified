---
agility: -1
ev: "6"
file_basename: mummy
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 3
item_id: mummy
item_name: Mummy
keywords:
    - Mummy
    - Undead
level: 4
might: 3
name: Mummy
organization: Horde
presence: 0
reason: 1
role: Brute
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/mummy
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "50"
type: statblock
weaknesses:
    - Fire 5
---

```ds-sb
agility: -1
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 3
          tier1: 6 corruption damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 8 corruption damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 10 corruption damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
        - effect: The next ability the mummy uses against the target has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increased by 1 for the target.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Accursed Bindings
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 3 corruption damage; I < 1 the target is cursed (save ends)
          tier2: 5 corruption damage; I < 2 the target is cursed (save ends)
          tier3: 7 corruption damage; I < 3 the target is cursed (save ends)
        - effect: A cursed target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), and allies gain an edge on strikes made against them.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Eldritch Curse
      target: One creature
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: 1 burst
      effects:
        - effect: The target takes 8 poison damage.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Blast of Mummy Dust
      target: The triggering creature
      trigger: The mummy comes within distance of a [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) creature or starts their turn within distance of one.
      type: feature
      usage: Triggered action
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 3
keywords:
    - Mummy
    - Undead
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/mummy
    source: mcdm.monsters.v1
might: 3
name: Mummy
organization: Horde
presence: 0
reason: 1
role: Brute
size: 1M
speed: 5
stability: 2
stamina: "50"
type: statblock
weaknesses:
    - Fire 5
```
