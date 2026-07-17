---
agility: 1
ev: 9 for four minions
file_basename: ogre-blue-blood
file_dpath: monster/ogre/statblock
free_strike: 4
intuition: 0
item_id: ogre-blue-blood
item_name: Ogre Blue Blood
keywords:
    - Giant
    - Ogre
level: 7
might: 4
name: Ogre Blue Blood
organization: Minion
presence: 2
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-blue-blood
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "13"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 1
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 7 damage; M < 3 [prone](../../../condition/prone.md)
          tier3: 8 damage; [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Crush Underfoot
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the blue blood would make a [free strike](../../../feature/common/main-actions/free-strike.md), an ally within 5 squares can make a [free strike](../../../feature/common/main-actions/free-strike.md) instead.
      feature_type: trait
      icon: ⭐️
      name: In My Stead
      type: feature
    - effects:
        - effect: The blue blood has damage immunity 2 while their squad has three or fewer minions in it.
      feature_type: trait
      icon: ⭐️
      name: Royal Anger
      type: feature
free_strike: 4
intuition: 0
keywords:
    - Giant
    - Ogre
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-blue-blood
    source: mcdm.monsters.v1
might: 4
name: Ogre Blue Blood
organization: Minion
presence: 2
reason: -1
role: Brute
size: "2"
speed: 5
stability: 4
stamina: "13"
type: statblock
with_captain: Gain an edge on strikes
```
