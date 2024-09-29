# Frame Factory

| goal                | amount | aluminum casing | nitrogen gas | iron ore | coal | limestone |
|---------------------|-------:|----------------:|-------------:|---------:|-----:|----------:|
| fused modular frame |     10 |             500 |          250 |    2 400 |  900 |       900 |
| heavy modular frame |     10 |             500 |          250 |    2 400 |  900 |       900 |

| input                    | amount |
|--------------------------|-------:|
| aluminum casing (import) |    500 |
| nitrogen gas (import)    |    250 |
| iron ore                 |  2 400 |
| coal                     |    900 |
| limestone                |    900 |

| product                 | amount | producers      | blueprint                          | amount |
|-------------------------|-------:|----------------|------------------------------------|-------:|
| fused modular frame     |     10 | 6,67 &rarr; 7  | `prod-mk5-mk2-fused_modular_frame` |      7 |
| heavy mocular frame     |     10 | 5 &rarr; 5     | `prod-mk5-heavy_modular_frame`     |      5 |
| encased industrial beam |     50 | 8,33 &rarr; 12 | `prod-mk5-encased_industrial_beam` |      2 |
| steel pipe              |    200 | 10 &rarr; 12   | `prod-mk5-steel_pipe`              |      1 |
| steel beam              |    150 | 10 &rarr; 12   | `prod-mk5-steel_beam`              |      1 |
| steel ingot             |    900 | 20 &rarr; 24   | `prod-mk5-steel_ingot`             |  2 + 2 |
| concrete                |    300 | 20 &rarr; 24   | `prod-mk5-concrete`                |  1 + 1 |
| modular frame           |     50 | 25 &rarr; 30   | `prod-mk5-modular_frame`           |      5 |
| reinforced iron plate   |     75 | 15 &rarr; 15   | `prod-mk5-reinforced_iron_plate`   |      5 |
| iron rod                |    825 | 55 &rarr; 60   | `prod-mk5-iron_rod`                |  2 + 3 |
| iron plate              |    450 | 22,5 &rarr; 24 | `prod-mk5-iron_plate`              |      2 |
| iron ingot              |  1 500 | 50 &rarr; 64   | `prod-mk5-iron_ingot`              |  2 + 2 |

# Train Stations
|                     |                      |
|---------------------|----------------------|
| fused modular frame | nitrogen gas (in)    |
| heavy modular frame | aluminum casing (in) |
|                     | (coal (in))          |
|                     | (coal (in))          |

# Production Floor
|                                    |                            |                                      |                                      |
|------------------------------------|----------------------------|--------------------------------------|--------------------------------------|
| 2 `prod-mk5-iron_ingot`            | 2 `prod-mk5-iron_ingot`    | 2 `prod-mk5-steel_ingot`             | 2 `prod-mk5-steel_ingot`             |
| 3 `prod-mk5-iron_rod`              | 2 `prod-mk5-iron_rod`      | 1 `prod-mk5-steel_beam`              | 1 `prod-mk5-concrete`                |
| 2 `prod-mk5-iron_plate`            | 1 `prod-mk5-steel_pipe`    | 2 `prod-mk5-encased_industrial_beam` | 1 `prod-mk5-concrete`                |
| 8 `prod-mk5-reinforced_iron_plate` | 5 `prod-mk5-modular_frame` | 5 `prod-mk5-heavy_modular_frame`     | 7 `prod-mk5-mk2-fused_modular_frame` |

## Needed to Build

| blueprints                         | amount |
|------------------------------------|-------:|
| `prod-mk5-mk2-fused_modular_frame` |      7 |
| `prod-mk5-heavy_modular_frame`     |      5 |
| `prod-mk5-encased_industrial_beam` |      2 |
| `prod-mk5-steel_pipe`              |      1 |
| `prod-mk5-steel_beam`              |      1 |
| `prod-mk5-steel_ingot`             |      4 |
| `prod-mk5-concrete`                |      2 |
| `prod-mk5-modular_frame`           |      5 |
| `prod-mk5-reinforced_iron_plate`   |      8 |
| `prod-mk5-iron_rod`                |      5 |
| `prod-mk5-iron_plate`              |      2 |
| `prod-mk5-iron_ingot`              |      4 |
|                                    |        |
| `prod-floor-empty`                 |      8 |
| `prod-floor-1-1`                   |     11 |
| `prod-floor-2-1`                   |      2 |
| `prod-floor-2i-1`                  |      1 |
| `prod-floor-4i-1`                  |      1 |
| `prod-floor-2-1-1-0`               |      1 |
|                                    |        |
| `prod-floor-corner`                |     30 |
| `prod-floor-corner_pillar`         |     15 |
| `prod-floor-connect`               |     40 |
| `prod-floor-connect_stairs`        |     36 |
