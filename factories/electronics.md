# Electronics Factory

| goal                 | amount | plastic | aluminum casing | caterium | copper | iron | quartz |
|----------------------|-------:|--------:|----------------:|---------:|-------:|-----:|-------:|
| supercomputer        |   4,76 |  779,86 |               0 |   594,05 | 752,08 |    0 |      0 |
| computer             |     25 |     800 |               0 |        0 |    600 |    0 |      0 |
| AI limiter           |     50 |       0 |               0 |      600 |    500 |    0 |      0 |
| high-speed connector |  17,85 |   71,40 |               0 |   599,76 | 249,90 |    0 |      0 |
| radio control unit   |     25 |     800 |             400 |        0 |    775 |  375 |    375 |
| crystal oscillator   |     20 |       0 |               0 |        0 |    280 |  600 |    600 |
| quartz crystal       |    360 |       0 |               0 |        0 |      0 |    0 |    600 |
| quickwire            |    720 |       0 |               0 |      432 |      0 |    0 |      0 |

| input           | amount |
|-----------------|-------:|
| plastic         |    800 |
| aluminum casing |    400 |
| caterium ore    |    780 |
| copper ore      |    775 |
| iron ore        |    600 |
| raw quartz      |    600 |

| product               | amount | producers   | blueprint | amount | max                  |
|-----------------------|-------:|-------------|-----------|-------:|----------------------|
| supercomputer         |   4,76 | 2,54 -> 4   |           |      2 | supercomputer        |
| radio control unit    |     25 | 10 -> 10    |           |      5 | radio control unit   |
| computer              |     25 | 10 -> 10    |           |      5 | radio control unit   |
| AI limiter            |     50 | 10 -> 10    |           |      5 | AI limiter           |
| high-speed connector  |  17,85 | 4,76 -> 5   |           |      5 | high-speed connector |
| crystal oscillator    |     20 | 20 -> 20    |           |     10 | crystal oscillator   |
| circuit board         |    100 | 13,33 -> 18 |           |      3 | radio control unit   |
| cable                 |    375 | 12,5 -> 18  |           |      3 | supercomputer        |
| copper sheet          |    325 | 25 -> 36    |           |      3 | AI limiter           |
| copper ingot          |    775 | 25,83 -> 32 |           |      2 | radio control unit   |
| caterium ingot        |    200 | 13,33 -> 16 |           |      2 | AI limiter           |
| reinforced iron plate |     50 | 10 -> 10    |           |      5 | crystal oscillator   |
| iron rod              |    150 | 10 -> 12    |           |      1 | crystal oscillator   |
| iron plate            |    300 | 15 -> 24    |           |      2 | crystal oscillator   |
| iron ingot            |    600 | 20 -> 32    |           |      2 | crystal oscillator   |
| quartz crystal        |    360 | 16 -> 24    |           |      2 | quartz crystal       |
| quickwire             |    720 | 12 -> 12    |           |      1 | quickwire            |


## Production Floor

|                               |                                  |                                 |                           |                      |
|-------------------------------|----------------------------------|---------------------------------|---------------------------|----------------------|
| `prod-mk5-iron_plate`         | `prod-mk5-iron_ingot`            | `prod-mk5-iron_rod`             | `prod-mk5-copper_ingot`   |                      |
| `prod-mk5-quartz_crystal`     | `prod-mk5-reinforced_iron_plate` | `prod-mk5-cable`                | `prod-mk5-copper_sheet`   |                      |
| `prod-mk5-crystal_oscillator` | `prod-mk5-circuit_board`         | `prod-mk5-high-speed_connector` | `prod-mk5-caterium_ingot` |                      |
| `prod-mk5-radio_control_unit` | `prod-mk5-computer`              | `prod-mk5-supercomputer`        | `prod-mk5-AI_limiter`     | `prod-mk5-quickwire` |

## Needed to Build

| blueprints                       | amount |
|----------------------------------|-------:|
| `prod-mk5-supercomputer`         |      2 |
| `prod-mk5-radio_control_unit`    |      5 |
| `prod-mk5-computer`              |      5 |
| `prod-mk5-AI_limiter`            |      5 |
| `prod-mk5-high-speed_connector`  |      5 |
| `prod-mk5-crystal_oscillator`    |     10 |
| `prod-mk5-circuit_board`         |      3 |
| `prod-mk5-cable`                 |      3 |
| `prod-mk5-copper_sheet`          |      3 |
| `prod-mk5-copper_ingot`          |      2 |
| `prod-mk5-caterium_ingot`        |      2 |
| `prod-mk5-reinforced_iron_plate` |      5 |
| `prod-mk5-iron_rod`              |      1 |
| `prod-mk5-iron_plate`            |      2 |
| `prod-mk5-iron_ingot`            |      2 |
| `prod-mk5-quartz_crystal`        |      2 |
| `prod-mk5-quickwire`             |      1 |
|                                  |        |
| `prod-floor-1-1`                 |      8 |
| `prod-floor-1-2-wire-cable`      |      1 |
| `prod-floor-2-1`                 |      1 |
| `prod-floor-2i-1`                |      2 |
| `prod-floor-3-1`                 |      3 |
| `prod-floor-3i-1`                |      1 |
| `prod-floor-4-1`                 |      1 |

| needed | amount | stacks |
|--------|--------|--------|
