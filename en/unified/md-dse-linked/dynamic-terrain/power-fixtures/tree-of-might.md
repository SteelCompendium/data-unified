---
features:
    - body: The tree of might must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: At the start of each round while the tree of might is intact, each enemy touching the ground in the encounter area who has M < 0 takes 10 corruption damage, and the tree of might grows a fruit. The [potency](../../rule/character/potency.md) increases by 1 each subsequent round.
      icon: ⭐️
      name: Tree's Nourishment
    - body: Once per round, any creature [adjacent](../../rule/combat/adjacent.md) to the tree of might can take a fruit from the tree and eat it (no action required). The creature gains 10 [temporary Stamina](../../rule/health/temporary-stamina.md) and has their Might score increased by 1 (to a maximum of 6) until the end of the encounter.
      icon: ⭐️
      name: Mighty Fruit
file_basename: tree-of-might
file_dpath: dynamic-terrain/power-fixtures
flavor: A gnarled tree has unearthed roots that writhe and curl.
item_id: tree-of-might
item_name: Tree of Might
level: 5
name: Tree of Might
role: Hexer
scc: mcdm.monsters.v1/dynamic-terrain.power-fixtures/tree-of-might
source: mcdm.monsters.v1
stats:
    - name: EV
      value: "14"
    - name: Stamina
      value: "60"
    - name: Size
      value: "3"
    - name: Immunity
      value: 5 to all damage except corruption or fire damage
terrain_type: Hazard
type: dynamic-terrain
---

```ds-fb
features:
    - body: The tree of might must be completely destroyed.
      icon: "\U0001F300"
      name: Deactivate
    - body: At the start of each round while the tree of might is intact, each enemy touching the ground in the encounter area who has M < 0 takes 10 corruption damage, and the tree of might grows a fruit. The [potency](../../rule/character/potency.md) increases by 1 each subsequent round.
      icon: ⭐️
      name: Tree's Nourishment
    - body: Once per round, any creature [adjacent](../../rule/combat/adjacent.md) to the tree of might can take a fruit from the tree and eat it (no action required). The creature gains 10 [temporary Stamina](../../rule/health/temporary-stamina.md) and has their Might score increased by 1 (to a maximum of 6) until the end of the encounter.
      icon: ⭐️
      name: Mighty Fruit
flavor: A gnarled tree has unearthed roots that writhe and curl.
level: 5
metadata:
    scc: mcdm.monsters.v1/dynamic-terrain.power-fixtures/tree-of-might
    source: mcdm.monsters.v1
name: Tree of Might
role: Hexer
stats:
    - name: EV
      value: "14"
    - name: Stamina
      value: "60"
    - name: Size
      value: "3"
    - name: Immunity
      value: 5 to all damage except corruption or fire damage
terrain_type: Hazard
type: dynamic-terrain
```
