---
features:
    - icon: "\U0001F300"
      intro: The throne of A'An can be deactivated only by the current hierophant of A'An (see **Sitting on the Throne**), who must succeed on a **Presence test** that takes a bane to do so.
      name: Deactivate
      power_roll:
        tiers:
            high: The throne is deactivated until the end of the encounter.
            low: The hierophant triggers the **Nova** ability.
            mid: The hierophant fails to deactivate the throne.
    - body: |-
        In the Age of Suns, there was no darkness and no night. Even among the many suns of that time, the light of A'An was the brightest. The throne of A'An manifests the sun powers of that god, even when no one is seated in it. The following effects always occur within 10 squares of the throne:

        - The throne sheds bright light that negates all darkness and concealment, and which prevents creatures from being hidden. - Any creature with cold immunity has fire weakness 10. - Any creature who uses an ability that deals cold damage takes 11 fire damage.
      icon: ⭐️
      name: Light of the Northern Sun
    - icon: ⭐️
      intro: Only a creature attuned to the throne can sit on it. A creature [adjacent](../../rule/combat/adjacent.md) to the throne can use a main action to attune to it by succeeding on a **Presence test**.
      name: Sitting on the Throne
      power_roll:
        tiers:
            high: The creature attunes to the throne and can sit on it.
            low: The creature takes 11 fire damage.
            mid: The creature fails to attune to the throne.
      trailing: |-
        A creature seated on the throne becomes the hierophant of A'An and gains the following benefits:

        - The hierophant and each of their allies within 10 squares of the throne have fire immunity 10. - The hierophant and each of their allies within 10 squares of the throne can choose to have their abilities deal fire damage instead of their usual damage. - The hierophant has a +5 bonus to [stability](../../rule/character/stability.md), and any strike made against them takes a bane unless the attacker is also attuned to the throne. - The hierophant can use the **Primordial Flare** and **Solar Accretion** abilities.
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Primordial Flare
      power_roll:
        formula: + 3
        tiers:
            high: 14 fire damage
            low: 6 fire damage
            mid: 11 fire damage
      sections:
        - label: Effect
          text: The target has fire weakness 10 until the start of the hierophant's next turn.
      target: One creature or object
      usage: Maneuver
    - distance: Ranged 10
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Solar Accretion
      sections:
        - label: Trigger
          text: A target within distance is made [winded](../../rule/health/winded.md) or is reduced to 0 [Stamina](../../rule/health/stamina.md) by fire damage.
        - label: Effect
          text: If the hierophant is a hero, they gain 3 of their Heroic Resource. If the hierophant is a Director-controlled creature, the Director gains 3 [Malice](../../rule/monster/malice.md).
      target: One creature
      usage: Free triggered action
    - distance: 10 burst
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Nova
      sections:
        - label: Trigger
          text: The throne is destroyed or the hierophant obtains a tier 1 outcome on the test to deactivate it.
        - label: Effect
          text: Each target takes 14 fire damage and the Hierophant gains the Incubator of A'An complication (see the sidebar). If there is no hierophant, one creature within 10 squares of the throne chosen by the Director gains this complication.
      target: Each creature and object in the area
      usage: Free triggered action
file_basename: the-throne-of-aan
file_dpath: dynamic-terrain/supernatural-objects
flavor: The throne of A'An, sun god of the Antical Protectorate in what is now Vanigar, retains some of her power from the age before she was slain to end the Age of Suns—and plunge the region into eternal winter.
item_id: the-throne-of-aan
item_name: The Throne of A'An
level: 4
name: The Throne of A'An
role: Controller
scc: mcdm.monsters.v1/dynamic-terrain.supernatural-objects/the-throne-of-aan
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "24"
    - name: Stamina
      value: "140"
    - name: Size
      value: "2"
terrain_type: Relic
type: dynamic-terrain
---

```ds-fb
features:
    - icon: "\U0001F300"
      intro: The throne of A'An can be deactivated only by the current hierophant of A'An (see **Sitting on the Throne**), who must succeed on a **Presence test** that takes a bane to do so.
      name: Deactivate
      power_roll:
        tiers:
            high: The throne is deactivated until the end of the encounter.
            low: The hierophant triggers the **Nova** ability.
            mid: The hierophant fails to deactivate the throne.
    - body: |-
        In the Age of Suns, there was no darkness and no night. Even among the many suns of that time, the light of A'An was the brightest. The throne of A'An manifests the sun powers of that god, even when no one is seated in it. The following effects always occur within 10 squares of the throne:

        - The throne sheds bright light that negates all darkness and concealment, and which prevents creatures from being hidden. - Any creature with cold immunity has fire weakness 10. - Any creature who uses an ability that deals cold damage takes 11 fire damage.
      icon: ⭐️
      name: Light of the Northern Sun
    - icon: ⭐️
      intro: Only a creature attuned to the throne can sit on it. A creature [adjacent](../../rule/combat/adjacent.md) to the throne can use a main action to attune to it by succeeding on a **Presence test**.
      name: Sitting on the Throne
      power_roll:
        tiers:
            high: The creature attunes to the throne and can sit on it.
            low: The creature takes 11 fire damage.
            mid: The creature fails to attune to the throne.
      trailing: |-
        A creature seated on the throne becomes the hierophant of A'An and gains the following benefits:

        - The hierophant and each of their allies within 10 squares of the throne have fire immunity 10. - The hierophant and each of their allies within 10 squares of the throne can choose to have their abilities deal fire damage instead of their usual damage. - The hierophant has a +5 bonus to [stability](../../rule/character/stability.md), and any strike made against them takes a bane unless the attacker is also attuned to the throne. - The hierophant can use the **Primordial Flare** and **Solar Accretion** abilities.
    - distance: Ranged 20
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Primordial Flare
      power_roll:
        formula: + 3
        tiers:
            high: 14 fire damage
            low: 6 fire damage
            mid: 11 fire damage
      sections:
        - label: Effect
          text: The target has fire weakness 10 until the start of the hierophant's next turn.
      target: One creature or object
      usage: Maneuver
    - distance: Ranged 10
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Solar Accretion
      sections:
        - label: Trigger
          text: A target within distance is made [winded](../../rule/health/winded.md) or is reduced to 0 [Stamina](../../rule/health/stamina.md) by fire damage.
        - label: Effect
          text: If the hierophant is a hero, they gain 3 of their Heroic Resource. If the hierophant is a Director-controlled creature, the Director gains 3 [Malice](../../rule/monster/malice.md).
      target: One creature
      usage: Free triggered action
    - distance: 10 burst
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Nova
      sections:
        - label: Trigger
          text: The throne is destroyed or the hierophant obtains a tier 1 outcome on the test to deactivate it.
        - label: Effect
          text: Each target takes 14 fire damage and the Hierophant gains the Incubator of A'An complication (see the sidebar). If there is no hierophant, one creature within 10 squares of the throne chosen by the Director gains this complication.
      target: Each creature and object in the area
      usage: Free triggered action
flavor: The throne of A'An, sun god of the Antical Protectorate in what is now Vanigar, retains some of her power from the age before she was slain to end the Age of Suns—and plunge the region into eternal winter.
level: 4
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.supernatural-objects/the-throne-of-aan
    source: mcdm.monsters.v1
name: The Throne of A'An
role: Controller
stats:
    - name: EV
      value: "24"
    - name: Stamina
      value: "140"
    - name: Size
      value: "2"
terrain_type: Relic
type: dynamic-terrain
```
