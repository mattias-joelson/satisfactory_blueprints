# Main Starter Base

## Mk3 Version

| goal                    | amount | iron ore | copper ore | limestone |   coal |
|-------------------------|-------:|---------:|-----------:|----------:|-------:|
| iron plate              |    180 |      270 |          0 |         0 |      0 |
| iron rod                |    270 |      270 |          0 |         0 |      0 |
| reinforced iron plate   |     30 |      360 |          0 |         0 |      0 |
| rotor                   |  43,20 |      486 |          0 |         0 |      0 |
| modular frame           |     20 |      480 |          0 |         0 |      0 |
| wire                    |    270 |        0 |        135 |         0 |      0 |
| cable                   |    270 |        0 |        270 |         0 |      0 |
| copper sheet            |    120 |        0 |        240 |         0 |      0 |
| concrete                |    180 |        0 |          0 |       540 |      0 |
| steel beam              |  67,50 |      270 |          0 |         0 |    270 |
| steel pipe              |    180 |      270 |          0 |         0 |    270 |
| encased industrial beam |  22,50 |      270 |          0 |       405 |    270 |
| motor                   |  21,60 |   680,40 |     172,80 |         0 | 194,40 |
|                         |        |          |            |           |        |
| smart plating           |     30 |   697,50 |          0 |         0 |      0 |
| versatile framework     |  11,25 |      405 |          0 |         0 |    270 |
| automated wiring        |  11,25 |    50,63 |        270 |         0 |    270 |
|                         |        |          |            |           |        |
| biofuel                 |      0 |        0 |          0 |         0 |      0 |
| biomass                 |      0 |        0 |          0 |         0 |      0 |
|                         |        |          |            |           |        |
| nobelisk                |     60 |      180 |          0 |         0 |    180 |
| rifle ammo              |    270 |        0 |        108 |         0 |      0 |
| SAM fluctuator          |     20 |       90 |         50 |         0 |     90 |
| heavy modular frame     |      2 |      480 |          0 |       180 |    180 |
| computer                |      5 |        0 |        120 |         0 |      0 |

| input                 | amount |
|-----------------------|-------:|
| iron ore              | 697,50 |
| copper ore            |    270 |
| limestone             |    540 |
| coal                  |    270 |
| plastic (in)          |    160 |
| black powder (in)     |    120 |
| smokeless powder (in) |     36 |
| reanimated SAM (in)   |      0 |

| product                 | amount | producers         | blueprint                          |    amount | max                     |
|-------------------------|-------:|-------------------|------------------------------------|----------:|-------------------------|
| motor                   |  21,60 | 4,32 &rarr; 6     | `prod-mk3-motor`                   |         1 | motor                   |
| stator                  |  43,20 | 8,64 &rarr; 9     | `prod-mk3-stator`                  |         3 | motor                   |
| modular frame           |     20 | 10 &rarr; 12      | `prod-mk3-modular_frame`           |         2 | modular frame           |
| reinforced iron plate   |     30 | 6 &rarr; 6        | `prod-mk3-reinforced_iron_plate`   |         2 | reinforced iron plate   |
| rotor                   |  43,20 | 10,80 &rarr; 12   | `prod-mk3-rotor`                   |         6 | rotor                   |
| iron plate              |    180 | 9 &rarr; 12       | `prod-mk3-iron_plate`              |         1 | iron plate              |
| iron rod                |    486 | 32,4 &rarr; 48    | `prod-mk3-iron_rod`                |     2 + 2 | iron rod                |
| iron ingot              |    486 | 16,20 &rarr; 48   | `prod-mk3-iron_ingot`              | 1 + 1 + 1 | rotor                   |
| cable                   |    270 | 9 &rarr; 18 @ 50% | `prod-mk3-cable`                   |         3 | cable                   |
| wire                    |    270 | 9 &rarr; 12       | `prod-mk3-wire`                    |         1 | wire                    |
| copper sheet            |    120 | 12 &rarr; 12      | `prod-mk3-copper_sheet`            |         1 | copper sheet            |
| copper ingot            |    270 | 9 &rarr; 16       | `prod-mk3-copper_ingot`            |         1 | cable                   |
| encased industrial beam |  22,50 | 3,75 &rarr; 6     | `prod-mk3-encased_industrial_beam` |         1 | encased industrial beam |
| concrete                |    180 | 12 &rarr; 24      | `prod-mk3-concrete`                |     1 + 1 | concrete                |
| steel beam              |  67,50 | 4,50 &rarr; 12    | `prod-mk3-steel_beam`              |         1 | steel beam              |
| steel pipe              |    180 | 9 &rarr; 12       | `prod-mk3-steel_pipe`              |         1 | steel pipe              |
| steel ingot             |    270 | 6 &rarr; 12       | `prod-mk3-steel_ingot`             |     1 + 1 | steel beam              |
|                         |        |                   |                                    |           |                         |
| smart plating           |     30 | 15 &rarr; 18      | `prod-mk3-smart_plating`           |         3 | smart plating           |
| versatile framework     |  11,25 | 2,25 &rarr; 6     | `prod-mk3-versatile_framework`     |         1 | versatile framework     |
| automated wiring        |  11,25 | 4,50 &rarr; 6     | `prod-mk3-automated_wiring`        |         1 | automated wiring        |

|                            |                                    |                            |                         |                         |                          |                                                   |                                      |
|----------------------------|------------------------------------|----------------------------|-------------------------|-------------------------|--------------------------|---------------------------------------------------|--------------------------------------|
| 1 `prod-mk3-wire`          | 1 `prod-mk3-automated_wiring`      | 3 `prod-mk3-smart_plating` |                         | **elevator**            |                          | 1 `prod-mk3-versatile_framework`                  |                                      |
| 1 `prod-mk3-copper_ingot`  | 1 `prod-mk3-iron_ingot`            | 1 `prod-mk3-iron_ingot`    | 1 `prod-mk3-iron_ingot` | **blueprint**           | 1 `prod-mk3-steel_ingot` | 1 `prod-mk3-steel_ingot`                          | 1 `prod-mk3-concrete`                |
| 3 `prod-mk3-cable`         | 1 `prod-mk3-iron_plate`            | 2 `prod-mk3-iron_rod`      | 2 `prod-mk3-iron_rod`   | **hub**                 | 1 `prod-mk3-steel_pipe`  | 1 `prod-mk3-steel_beam`                           | 1 `prod-mk3-concrete`                |
| 1 `prod-mk3-copper_sheet`  | 2 `prod-mk3-reinforced_iron_plate` | 2 `prod-mk3-modular_frame` | 6 `prod-mk3-rotor`      | 1 `prod-module-storage` | 1 `prod-mk3-motor`       | 3 `prod-mk3-stator`                               | 1 `prod-mk3-encased_industrial_beam` |
| 1 `prod-mk3-circuit_board` | 1 `prod-mk3-heavy_modular_frame`   | **train**                  | **train**               | **train**               | **train**                | 1 `pow-mk3-biofuel`<br>1 `pow-mk3-biomass_burner` | >= 1 `pow-power_storage`             |
| 1 `prod-mk3-computer`      | 1 `prod-mk3-rifle_ammo`            | **train**                  | **train**               | **train**               | **train**                | 1 `prod-mk3-nobelisk`                             | 1 `prod-mk3-SAM_fluctuator`          |

| blueprints                         | amount |
|------------------------------------|-------:|
| `prod-mk3-motor`                   |      1 |
| `prod-mk3-stator`                  |      3 |
| `prod-mk3-modular_frame`           |      2 |
| `prod-mk3-reinforced_iron_plate`   |      2 |
| `prod-mk3-rotor`                   |      6 |
| `prod-mk3-iron_plate`              |      1 |
| `prod-mk3-iron_rod`                |      4 |
| `prod-mk3-iron_ingot`              |      3 |
| `prod-mk3-cable`                   |      3 |
| `prod-mk3-wire`                    |      1 |
| `prod-mk3-copper_sheet`            |      1 |
| `prod-mk3-copper_ingot`            |      1 |
| `prod-mk3-encased_industrial_beam` |      1 |
| `prod-mk3-concrete`                |      2 |
| `prod-mk3-steel_beam`              |      1 |
| `prod-mk3-steel_pipe`              |      1 |
| `prod-mk3-steel_ingot`             |      2 |
| `prod-mk3-smart_plating`           |      3 |
| `prod-mk3-versatile_framework`     |      1 |
| `prod-mk3-automated_wiring`        |      1 |
| `pow-mk3-biofuel`                  |      1 |
| `pow-mk3-biomass_burner`           |      1 |
| `pow-power_storage`                |   >= 1 |
| `prod-mk3-nobelisk`                |      1 |
| `prod-mk3-rifle_ammo`              |      1 |
| `prod-mk3-SAM_fluctuator`          |      1 |
| `prod-mk3-heavy_modular_frame`     |      1 |
| `prod-mk3-circuit_board`           |      1 |
| `prod-mk3-computer`                |      1 |
| `prod-module-storage`              |      1 |
|                                    |        |
| `prod-parts-production_floor`      |      1 |
| `prod-floor-empty`                 |      1 |
| `prod-floor-1-1`                   |     13 |
| `prod-floor-1-1-cable`             |      1 |
| `prod-floor-2-1`                   |     11 |
| `prod-floor-2i-1`                  |      3 |
| `prod-floor-3-1`                   |      1 |
| `prod-floor-3i-1`                  |      1 |
| `prod-floor-4i-1`                  |      1 |
| `prod-floor-storage`               |      1 |

## Mk5 Version

| goal                    | amount | iron ore | copper ore | limestone |   coal |
|-------------------------|-------:|---------:|-----------:|----------:|-------:|
| iron plate              |    520 |      780 |          0 |         0 |      0 |
| iron rod                |    780 |      780 |          0 |         0 |      0 |
| reinforced iron plate   |  86,66 |     1040 |          0 |         0 |      0 |
| rotor                   | 124,80 |     1404 |          0 |         0 |      0 |
| modular frame           |  57,77 | 1 386,67 |          0 |         0 |      0 |
| wire                    |    780 |        0 |        390 |         0 |      0 |
| cable                   |    780 |        0 |        780 |         0 |      0 |
| copper sheet            |    390 |        0 |        780 |         0 |      0 |
| concrete                |    520 |        0 |          0 |     1 560 |      0 |
| steel beam              |    195 |      780 |          0 |         0 |    780 |
| steel pipe              |    520 |      780 |          0 |         0 |    780 |
| encased industrial beam |     65 |      780 |          0 |     1 170 |    780 |
| motor                   |  62,40 | 1 965,60 |     499,20 |         0 | 499,20 |
|                         |        |          |            |           |        |
| smart plating           |  86,66 |    2 015 |          0 |         0 |      0 |
| versatile framework     |  32,50 |    1 170 |          0 |         0 |    780 |
| automated wiring        |  32,50 |   146,25 |        780 |         0 | 146,25 |
|                         |        |          |            |           |        |
| biomass                 |        |          |            |           |        |
|                         |        |          |            |           |        |
| nobelisk                |     60 |      180 |          0 |         0 |    180 |
| rifle ammo              |    270 |        0 |        108 |         0 |      0 |
| SAM fluctuator          |        |          |            |           |        |
| heavy modular frame *** |      3 |      720 |          0 |       270 |    270 |
| computer                |  11,25 |        0 |        270 |         0 |      0 |

| input      | amount |
|------------|-------:|
| iron ore   |        |
| copper ore |        |
| limestone  |        |
| coal       |        |

| product                 | amount | producers           | blueprint                          |    amount | max                     |
|-------------------------|-------:|---------------------|------------------------------------|----------:|-------------------------|
| motor                   |   62,4 | 12,48 &rarr; 18     | `prod-mk5-motor`                   |         3 | motor                   |
| stator                  | 124,80 | 24,96 &rarr; 27     | `prod-mk5-stator`                  |         9 | motor                   |
| modular frame           |  57,77 | 28,89 &rarr; 30     | `prod-mk5-modular_frame`           |         5 | modular frame           |
| reinforced iron plate   |  86,66 | 17,33 &rarr; 18     | `prod-mk5-reinforced_iron_plate`   |         6 | reinforced iron plate   |
| rotor                   | 124,80 | 31,20 &rarr; 32     | `prod-mk5-rotor`                   |        16 | rotor                   |
| iron plate              |    520 | 26 &rarr; 36        | `prod-mk5-iron_plate`              |         3 | iron plate              |
| iron rod                |  1 404 | 93,6 &rarr; 120     | `prod-mk5-iron_rod`                |     5 + 5 | rotor                   |
| iron ingot              |  2 015 | 67,17 &rarr; 96     | `prod-mk5-iron_ingot`              | 2 + 2 + 2 | smart plating           |
| cable                   |    780 | 26 &rarr; 54 @ 50 % | `prod-mk5-cable`                   |         9 | cable                   |
| wire                    |    780 | 26 &rarr; 36        | `prod-mk5-wire`                    |         3 | wire                    |
| copper sheet            |    390 | 39 &rarr; 48        | `prod-mk5-copper_sheet`            |         4 | copper sheet            |
| copper ingot            |    780 | 26 &rarr; 32        | `prod-mk5-copper_ingot`            |         2 | cable                   |
| encased industrial beam |     65 | 10,83 &rarr; 12     | `prod-mk5-encased_industrial_beam` |         2 | encased industrial beam |
| concrete                |    520 | 34,67 &rarr; 48     | `prod-mk5-concrete`                |     2 + 2 | concrete                |
| steel beam              |    195 | 13 &rarr; 24        | `prod-mk5-steel_beam`              |         2 | steel beam              |
| steel pipe              |    520 | 26 &rarr; 36        | `prod-mk5-steel_pipe`              |         3 | steel pipe              |
| steel ingot             |    780 | 17,33 &rarr; 18     | `prod-mk5-steel_ingot`             |     3 + 3 | steel beam              |
|                         |        |                     |                                    |           |                         |
| smart plating           |  86,66 | 43,33 &rarr; 48     | `prod-mk5-smart_plating`           |         8 | smart plating           |
| versatile framework     |  32,50 | 6,50 &rarr; 12      | `prod-mk5-versatile_framework`     |         2 | versatile framework     |
| automated wiring        |  32,50 | 13 &rarr; 18        | `prod-mk5-automated_wiring`        |         3 | automatic wiring        |

|                           |                                    |                            |                         |                         |                          |                                                   |                                      |
|---------------------------|------------------------------------|----------------------------|-------------------------|-------------------------|--------------------------|---------------------------------------------------|--------------------------------------|
| 3 `prod-mk5-wire`         | 3 `prod-mk5-automated_wiring`      | 8 `prod-mk5-smart_plating` |                         | **elevator**            |                          | 2 `prod-mk5-versatile_framework`                  |                                      |
| 2 `prod-mk5-copper_ingot` | 2 `prod-mk5-iron_ingot`            | 2 `prod-mk5-iron_ingot`    | 2 `prod-mk5-iron_ingot` | **blueprint**           | 3 `prod-mk5-steel_ingot` | 3 `prod-mk5-steel_ingot`                          | 2 `prod-mk5-concrete`                |
| 9 `prod-mk5-cable`        | 3 `prod-mk5-iron_plate`            | 5 `prod-mk5-iron_rod`      | 5 `prod-mk5-iron_rod`   | **hub**                 | 3 `prod-mk5-steel_pipe`  | 2 `prod-mk5-steel_beam`                           | 2 `prod-mk5-concrete`                |
| 4 `prod-mk5-copper_sheet` | 6 `prod-mk5-reinforced_iron_plate` | 5 `prod-mk5-modular_frame` | 16 `prod-mk5-rotor`     | 1 `prod-module-storage` | 3 `prod-mk5-motor`       | 9 `prod-mk5-stator`                               | 2 `prod-mk5-encased_industrial_beam` |
|                           |                                    | **train**                  | **train**               | **train**               | **train**                | 1 `pow-mk5-biofuel`<br>1 `pow-mk5-biomass_burner` | >= 1 `pow-power_storage`             |
|                           | 1 `prod-mk5-rifle_ammo`            | **train**                  | **train**               | **train**               | **train**                | 1 `prod-mk5-nobelisk`                             | 1 `prod-mk5-SAM_fluctuator`          |
w
| blueprints                         | amount |
|------------------------------------|-------:|
| `prod-mk5-motor`                   |      3 |
| `prod-mk5-stator`                  |      9 |
| `prod-mk5-modular_frame`           |      5 |
| `prod-mk5-reinforced_iron_plate`   |      6 |
| `prod-mk5-rotor`                   |     16 |
| `prod-mk5-iron_plate`              |      3 |
| `prod-mk5-iron_rod`                |     10 |
| `prod-mk5-iron_ingot`              |      6 |
| `prod-mk5-cable`                   |      9 |
| `prod-mk5-wire`                    |      3 |
| `prod-mk5-copper_sheet`            |      4 |
| `prod-mk5-copper_ingot`            |      2 |
| `prod-mk5-encased_industrial_beam` |      2 |
| `prod-mk5-concrete`                |      4 |
| `prod-mk5-steel_beam`              |      2 |
| `prod-mk5-steel_pipe`              |      3 |
| `prod-mk5-steel_ingot`             |      6 |
| `prod-mk5-smart_plating`           |      8 |
| `prod-mk5-versatile_framework`     |      2 |
| `prod-mk5-automated_wiring`        |      3 |
| `pow-mk5-biofuel`                  |      1 |
| `pow-mk5-biomass_burner`           |      1 |
| `pow-power_storage`                |   >= 1 |
| `prod-mk5-nobelisk`                |      1 |
| `prod-mk5-rifle_ammo`              |      1 |
| `prod-mk5-SAM_fluctuator`          |      1 |
| `prod-module-storage`              |      1 |
|                                    |        |
| `prod-parts-production_floor`      |      3 |
| `prod-floor-empty`                 |      1 |
| `prod-floor-1-1`                   |     13 |
| `prod-floor-1-1-cable`             |      1 |
| `prod-floor-2-1`                   |     10 |
| `prod-floor-2i-1`                  |      3 |
| `prod-floor-3i-1`                  |      1 |
| `prod-floor-storage`               |      1 |
