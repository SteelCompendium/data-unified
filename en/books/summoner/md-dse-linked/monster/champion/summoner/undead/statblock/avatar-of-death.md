---
agility: 2
cost: 9 essence for one champion
cost_amount: "9"
cost_resource: essence for one champion
file_basename: avatar-of-death
file_dpath: monster/champion/summoner/undead/statblock
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
free_strike_damage_type: Holy
immunities:
    - Corruption 5
    - poison 5
intuition: 2
item_id: avatar-of-death
item_name: Avatar of Death
keywords:
    - Undead
might: 5
movement: Fly
name: Avatar of Death
organization: Champion
presence: 2
reason: 5
scc: mcdm.summoner.v1/monster.champion.summoner.undead.statblock/avatar-of-death
size: "2"
source: mcdm.summoner.v1
speed: 6
stability: 3
stamina: SPECIAL
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 9 essence for one champion
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: 2d10 + 5
          tier1: 9 corruption [damage](../../../../../rule/damage/damage.md); M < WEAK [bleeding](../../../../../condition/bleeding.md) ([save ends](../../../../../rule/general/saving-throw.md))
          tier2: 12 corruption [damage](../../../../../rule/damage/damage.md); M < AVERAGE [bleeding](../../../../../condition/bleeding.md) ([save ends](../../../../../rule/general/saving-throw.md))
          tier3: 14 corruption [damage](../../../../../rule/damage/damage.md); M < STRONG [bleeding](../../../../../condition/bleeding.md) ([save ends](../../../../../rule/general/saving-throw.md))
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Culling Scythe
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: The Avatar's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) P < WEAK instantly reduce a [winded](../../../../../rule/health/winded.md) non-leader or solo creature to 0 [Stamina](../../../../../rule/health/stamina.md), including targets [winded](../../../../../rule/health/winded.md) by the [strike](../../../../../rule/combat/strike.md).
      feature_type: trait
      icon: ⭐️
      name: Revelation Strike
      type: feature
    - effects:
        - effect: If the Avatar only targets one creature or object with a [strike](../../../../../rule/combat/strike.md), they deal additional [damage](../../../../../rule/damage/damage.md) to the target equal to your [Reason](../../../../../rule/character/reason.md).
      feature_type: trait
      icon: ⭐️
      name: Champion's Ire
      type: feature
    - distance: 1 burst
      effects:
        - effect: |-
            **Trigger:** The Avatar takes [damage](../../../../../rule/damage/damage.md).
            **Effect:** M < AVERAGE [weakened](../../../../../condition/weakened.md) ([EoT](../../../../../rule/combat/end-of-turn.md)).
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Dust and Rot
      target: Each enemy in the burst
      type: feature
      usage: Free triggered action
    - effects:
        - effect: The Avatar is unaffected by [difficult terrain](../../../../../movement/difficult-terrain.md) and [damage](../../../../../rule/damage/damage.md) from [forced movement](../../../../../movement/forced-movement.md).
      feature_type: trait
      icon: ⭐️
      name: Drifting Spirit
      type: feature
flavor: 'Stamina: Your maximum Stamina'
free_strike: 9
immunities:
    - Corruption 5
    - poison 5
intuition: 2
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.champion.summoner.undead.statblock/avatar-of-death
    source: mcdm.summoner.v1
might: 5
movement: Fly
name: Avatar of Death
organization: Champion
presence: 2
reason: 5
role: ""
size: "2"
speed: 6
stability: 3
stamina: SPECIAL
type: statblock
weaknesses: []
```
