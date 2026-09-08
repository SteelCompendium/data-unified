---
agility: -1
ev: "36"
file_basename: hill-giant-clobberer
file_dpath: monster/giant/statblock
free_strike: 8
immunities:
    - Damage 3
intuition: -1
item_id: hill-giant-clobberer
item_name: Hill Giant Clobberer
keywords:
    - Giant
    - Hill Giant
level: 7
might: 4
movement: Climb
name: Hill Giant Clobberer
organization: Elite
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.giant.statblock/hill-giant-clobberer
size: "4"
source: mcdm.monsters.v1
speed: 6
stability: 5
stamina: "200"
type: statblock
---

```ds-sb
agility: -1
ev: "36"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage
          tier2: 17 damage; [prone](../../../condition/prone.md)
          tier3: 21 damage; [prone](../../../condition/prone.md)
        - effect: A target who is already [prone](../../../condition/prone.md) takes an extra 12 damage.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Clobberin' Club
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 14 damage; [prone](../../../condition/prone.md)
          tier2: 20 damage; [prone](../../../condition/prone.md); M < 3 can't stand (save ends)
          tier3: 25 damage; [prone](../../../condition/prone.md); M < 4 can't stand (save ends)
        - effect: In suitably soft ground, the target is entrenched in a 2-square deep hole.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Stomp
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 3 burst
      effects:
        - effect: Each target must make either a **Might test** or an **Agility test**.
          name: Effect
          tier1: 6 damage; vertical [push](../../../movement/forced-movement.md) 3
          tier2: 2 damage; vertical [push](../../../movement/forced-movement.md) 2
          tier3: '[Push](../../../movement/forced-movement.md) 2'
        - effect: The clobberer can choose to fall [prone](../../../condition/prone.md) in order to double the [forced movement](../../../movement/forced-movement.md) distance.
          name: Effect
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Hill Quake
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Melee 3
      effects:
        - effect: The target makes an Agility test.
          name: Effect
          tier1: '[Grabbed](../../../condition/grabbed.md), and the target takes a bane on the Escape Grab maneuver'
          tier2: '[Grabbed](../../../condition/grabbed.md)'
          tier3: No effect
        - cost: 2 Malice
          effect: A target who would be [grabbed](../../../condition/grabbed.md) by this ability is instead either vertical [pushed](../../../movement/forced-movement.md) up to 5 squares; or they take 5 damage, are knocked [prone](../../../condition/prone.md), and can't stand until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: You Ain't Getting Away
      target: The triggering creature
      trigger: A creature within distance moves or [shifts](../../../movement/shifting.md) away from the clobberer.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The clobberer automatically destroys any mundane size 1 objects in their path when they move or are [forced moved](../../../movement/forced-movement.md). They can break through any mundane wall made of wood, stone, or a similarly sturdy material this way as long as the wall is 2 squares thick or less.
      feature_type: trait
      icon: ⭐️
      name: Destructive Path
      type: feature
    - effects:
        - effect: Whenever the clobberer targets a creature or object with an ability, any enemy within distance of the ability can use a free triggered action to distract the clobberer. The clobberer targets that enemy instead.
      feature_type: trait
      icon: ⭐️
      name: Distracted
      type: feature
free_strike: 8
immunities:
    - Damage 3
intuition: -1
keywords:
    - Giant
    - Hill Giant
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/hill-giant-clobberer
    source: mcdm.monsters.v1
might: 4
movement: Climb
name: Hill Giant Clobberer
organization: Elite
presence: -1
reason: -1
role: Brute
size: "4"
speed: 6
stability: 5
stamina: "200"
type: statblock
```
