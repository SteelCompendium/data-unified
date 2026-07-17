---
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a field ballista can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The field ballista is deactivated and can't be used.
            low: The creature accidentally activates the **Release Bolt** ability.
            mid: The field ballista is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Release Bolt
      power_roll:
        formula: + 2
        tiers:
            high: 11 damage; M < 2 push 2
            low: 5 damage
            mid: 8 damage; M < 1 push 1
      sections:
        - label: Effect
          text: This ability can't be used again until the field ballista is reloaded.
      target: One creature or object
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The field ballista is reloaded, allowing **Release Bolt** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Release Bolt** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The field ballista and the creature using this action move together up to 3 squares.
      target: '-'
      usage: Main action (Adjacent creature)
    - body: |-
        **Penetrating Bolt (+2 EV)** The field ballista targets the nearest two additional creatures or objects in a straight line beyond the initial target.

        **Chain Bolt (+2 EV)** The field ballista's bolts are set with heavy chains that wrap around targets. The **Chain Bolt** ability replaces **Release Bolt**, and the field ballista gains the **Crank the Chain** ability.
      icon: ⭐️
      name: Upgrades
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Chain Bolt
      power_roll:
        formula: + 2
        tiers:
            high: 10 damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 4 damage
            mid: 7 damage; M < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: This ability can't be used again until the field ballista is reloaded.
      target: One creature or object
      usage: Main action (Adjacent creature)
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Crank the Chain
      power_roll:
        formula: + 2
        tiers:
            high: Pull 5
            low: Pull 1
            mid: Pull 3
      sections:
        - label: Special
          text: The target must be [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by the field ballista.
        - label: Effect
          text: This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) triggers [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack).
      target: One creature
      usage: Main action (Adjacent creature)
file_basename: field-ballista
file_dpath: dynamic-terrain/siege-engines
flavor: A massive crossbow fires thick metal bolts with devastating effect.
item_id: field-ballista
item_name: Field Ballista
level: 2
name: Field Ballista
role: Artillery
scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/field-ballista
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "8"
    - name: Stamina
      value: "40"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: As a maneuver, a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a field ballista can make an **Agility test**.
      name: Deactivate
      power_roll:
        tiers:
            high: The field ballista is deactivated and can't be used.
            low: The creature accidentally activates the **Release Bolt** ability.
            mid: The field ballista is deactivated but the creature is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (EoT).
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Release Bolt
      power_roll:
        formula: + 2
        tiers:
            high: 11 damage; M < 2 push 2
            low: 5 damage
            mid: 8 damage; M < 1 push 1
      sections:
        - label: Effect
          text: This ability can't be used again until the field ballista is reloaded.
      target: One creature or object
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Reload
      sections:
        - label: Effect
          text: The field ballista is reloaded, allowing **Release Bolt** to be used again. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Spot
      sections:
        - label: Effect
          text: The next use of **Release Bolt** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.
      target: '-'
      usage: Main action (Adjacent creature)
    - distance: '-'
      icon: ⭐️
      name: Move
      sections:
        - label: Effect
          text: The field ballista and the creature using this action move together up to 3 squares.
      target: '-'
      usage: Main action (Adjacent creature)
    - body: |-
        **Penetrating Bolt (+2 EV)** The field ballista targets the nearest two additional creatures or objects in a straight line beyond the initial target.

        **Chain Bolt (+2 EV)** The field ballista's bolts are set with heavy chains that wrap around targets. The **Chain Bolt** ability replaces **Release Bolt**, and the field ballista gains the **Crank the Chain** ability.
      icon: ⭐️
      name: Upgrades
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Chain Bolt
      power_roll:
        formula: + 2
        tiers:
            high: 10 damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 4 damage
            mid: 7 damage; M < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: This ability can't be used again until the field ballista is reloaded.
      target: One creature or object
      usage: Main action (Adjacent creature)
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Crank the Chain
      power_roll:
        formula: + 2
        tiers:
            high: Pull 5
            low: Pull 1
            mid: Pull 3
      sections:
        - label: Special
          text: The target must be [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by the field ballista.
        - label: Effect
          text: This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) triggers [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack).
      target: One creature
      usage: Main action (Adjacent creature)
flavor: A massive crossbow fires thick metal bolts with devastating effect.
level: 2
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.siege-engines/field-ballista
    source: mcdm.monsters.v1
name: Field Ballista
role: Artillery
stats:
    - name: EV
      value: "8"
    - name: Stamina
      value: "40"
    - name: Size
      value: "2"
terrain_type: Siege Engine
type: dynamic-terrain
```
