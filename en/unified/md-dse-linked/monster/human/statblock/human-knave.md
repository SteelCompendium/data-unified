---
agility: 0
ev: "8"
file_basename: human-knave
file_dpath: monster/human/statblock
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
item_id: human-knave
item_name: Human Knave
keywords:
    - Human
    - Humanoid
level: 2
might: 2
name: Human Knave
organization: Platoon
presence: 0
reason: 1
role: Defender
scc: mcdm.monsters.v1/monster.human.statblock/human-knave
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 0
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage
          tier3: 12 damage; M < 2 the target has a double bane on their next power roll
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Morningstar and Javelin
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an [adjacent](../../../rule/combat/adjacent.md) creature the knave has [taunted](../../../condition/taunted.md) deals damage to a creature other than the knave, the knave can make a [free strike](../../../feature/common/main-actions/free-strike.md) against them.
      feature_type: trait
      icon: ⭐️
      name: I'm Your Enemy
      type: feature
    - effects:
        - effect: An enemy who starts their turn [adjacent](../../../rule/combat/adjacent.md) to the knave can't [shift](../../../movement/shifting.md).
      feature_type: trait
      icon: ⭐️
      name: Overwhelm
      type: feature
    - effects:
        - effect: The knave ignores concealment if it's granted by a supernatural effect.
      feature_type: trait
      icon: ⭐️
      name: Supernatural Insight
      type: feature
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.human.statblock/human-knave
    source: mcdm.monsters.v1
might: 2
name: Human Knave
organization: Platoon
presence: 0
reason: 1
role: Defender
size: 1M
speed: 5
stability: 0
stamina: "50"
type: statblock
```
