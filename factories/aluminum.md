# Aluminum Factory

| production (either)   | amount |
|-----------------------|-------:|
| alclad aluminum sheet |  1 440 |
| aluminum casing       |    960 |

| input        | amount |
|--------------|-------:|
| bauxite      |  1 440 |
| coal         |    720 |
| raw quartz   |    720 |
| copper ingot |    480 |
| water        |  1 440 |

| product               | amount | producers         | blueprint                                                                | amount |
|-----------------------|-------:|-------------------|--------------------------------------------------------------------------|-------:|
| alumina solution      |  1 440 | 12 &rarr; 12      | `prod-mk5-mk1-alumina_solution_LR`<br>`prod-mk5-mk1-alumina_solution_RL` |  2 + 2 |
| aluminum scrap        |  2 160 | 6 &rarr; 8 @ 75%  | `prod-mk5-mk1-aluminum_scrap_LR`<br>`prod-mk5-mk1-aluminum_scrap_RL`     |  2 + 2 |
| aluminum ingot        |  1 440 | 24 &rarr; 24      | `prod-mk5-aluminum_ingot` + `prod-mk5-aluminum_ingot_top`                |  3 + 3 |
| silica                |  1 200 | 32 &rarr; 12 + 24 | `prod-mk5-silica`                                                        |  2 + 1 |
| alclad aluminum sheet |  1 440 | 48 &rarr; 2 * 24  | `prod-mk5-alclad_aluminum_sheet`                                         |  4 + 4 |
| aluminum casing       |    960 | 16 &rarr; 2 * 12  | `prod-mk5-aluminum_casing`                                               |  1 + 1 |
| water                 |  1 440 | 12 &rarr; 12      | water extractor                                                          |     12 |

## Refinery Floor
|                                    |                                    |                                    |                                    |
|------------------------------------|------------------------------------|------------------------------------|------------------------------------|
| `prod-mk5-mk1-alumina_solution_LR` | `prod-mk5-mk1-alumina_solution_RL` | `prod-mk5-mk1-alumina_solution_LR` | `prod-mk5-mk1-alumina_solution_RL` |
| `prod-mk5-mk1-aluminum_scrap_LR`   | `prod-mk5-mk1-aluminum_scrap_RL`   | `prod-mk5-mk1-aluminum_scrap_LR`   | `prod-mk5-mk1-aluminum_scrap_RL`   |

## Production Floor

|                                                           |                                    |                                                           |                                                           |
|-----------------------------------------------------------|------------------------------------|-----------------------------------------------------------|-----------------------------------------------------------|
|                                                           |                                    | 2 `prod-mk5-silica`                                       | `prod-mk5-silica`                                         |
| `prod-mk5-aluminum_ingot` + `prod-mk5-aluminum_ingot_top` | `logi-balancer-4_4_mk5`            | `prod-mk5-aluminum_ingot` + `prod-mk5-aluminum_ingot_top` | `prod-mk5-aluminum_ingot` + `prod-mk5-aluminum_ingot_top` |
| 4 `prod-mk5-alclad_aluminum_sheet`                        | 4 `prod-mk5-alclad_aluminum_sheet` | `prod-mk5-aluminum_casing`                                | `prod-mk5-aluminum_casing`                                |

## Needed to Build

| blueprints                         | amount |
|------------------------------------|-------:|
| `prod-mk5-mk1-alumina_solution_LR` |      2 |
| `prod-mk5-mk1-alumina_solution_RL` |      2 |
| `prod-mk5-mk1-aluminum_scrap_LR`   |      2 |
| `prod-mk5-mk1-aluminum_scrap_RL`   |      2 |
| `prod-mk5-silica`                  |      3 |
| `prod-mk5-aluminum_ingot`          |      3 |
| `prod-mk5-aluminum_ingot_top`      |      3 |
| `logi-balancer-4_4_mk5`            |      1 |
| `prod-mk5-alclad_aluminum_sheet`   |      8 |
| `prod-mk5-aluminum_casing`         |      2 |

## Bonus
- copper ingot (for alclad aluminum sheet)
- hub (for mk5 logistics)
