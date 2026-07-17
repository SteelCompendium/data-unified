---
agility: 4
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: phantom-of-the-ripper
file_dpath: monster/minion/summoner/undead/statblock
flavor: These phantoms puppet the remnants of their corporeal forms. Unlike other spirits, the ripper tears the reality around them and leaves behind distorted or uneven "bumps" in the air, which can affect stone, metal, and flesh.
free_strike: 8
immunities:
    - Corruption R
    - poison R
intuition: 0
item_id: phantom-of-the-ripper
item_name: Phantom of the Ripper
keywords:
    - Undead
might: 0
movement: Fly, hover
name: Phantom of the Ripper
organization: Minion
presence: 3
reason: 0
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/phantom-of-the-ripper
size: 1M
source: mcdm.summoner.v1
speed: 6
stability: 1
stamina: 17 | 17
type: statblock
weaknesses: []
---

```ds-sb
agility: 4
cost: 7 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: 2d10 + R
          tier1: 8 [damage](../../../../../rule/damage/damage.md); A < WEAK [slowed](../../../../../condition/slowed.md) (save ends)
          tier2: 13 [damage](../../../../../rule/damage/damage.md); A < AVERAGE [slowed](../../../../../condition/slowed.md) (save ends)
          tier3: 17 [damage](../../../../../rule/damage/damage.md); A < STRONG [slowed](../../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Plunge of the Knife
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The phantom can move through other creatures and objects at normal speed. The first time in a [round](../../../../../rule/combat/combat-round.md) that the phantom passes through a creature, that creature takes 3 corruption [damage](../../../../../rule/damage/damage.md) and has a [bane](../../../../../rule/dice/bane.md) on their next [strike](../../../../../rule/combat/strike.md). The phantom doesn't take [damage](../../../../../rule/damage/damage.md) from being [force moved](../../../../../movement/forced-movement.md) into objects.
      feature_type: trait
      icon: ⭐️
      name: Ripping Phase
      type: feature
flavor: These phantoms puppet the remnants of their corporeal forms. Unlike other spirits, the ripper tears the reality around them and leaves behind distorted or uneven "bumps" in the air, which can affect stone, metal, and flesh.
free_strike: 8
immunities:
    - Corruption R
    - poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/phantom-of-the-ripper
    source: mcdm.summoner.v1
might: 0
movement: Fly, hover
name: Phantom of the Ripper
organization: Minion
presence: 3
reason: 0
role: Ambusher
size: 1M
speed: 6
stability: 1
stamina: 17 | 17
type: statblock
weaknesses: []
```
