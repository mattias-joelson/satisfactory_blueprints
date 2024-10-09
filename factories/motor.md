# Motor Factory

| goal           | amount | iron ore | copper ore | coal | water | nitrogen gas | rubber | alclad aluminum sheet | radio control unit |
|----------------|-------:|---------:|-----------:|-----:|------:|-------------:|-------:|----------------------:|-------------------:|
| turbo motor    |   12,5 |    1 575 |      1 000 |  450 |   250 |        1 250 |    400 |                   500 |                 25 |
| cooling system |     72 |        0 |        864 |    0 |   360 |        1 800 |    144 |                   720 |                  0 |

| input                          | amount |
|--------------------------------|-------:|
| rubber (import)                |    400 |
| alclad aluminum sheet (import) |    720 |
| nitrogen gas (import)          |  1 800 |
| iron ore                       |  1 575 |
| copper ore                     |  1 000 |
| coal                           |    450 |
| water                          |    360 |

| product        | amount | producers       | blueprint                     | amount | max            |
|----------------|-------:|-----------------|-------------------------------|-------:|----------------|
| turbo motor    |   12,5 | 6,67 &rarr; 8   | `prod-mk5-turbo_motor`        |  4 / 1 | turbo motor    |
| cooling system |     72 | 12 &rarr; 12    | `prod-mk5-mk2-cooling_system` | 12 / 3 | cooling system |
| water          |    360 | 3 &rarr; 3      | water extractor               |      3 | cooling system |
| heat sink      |    144 | 19,20 &rarr; 24 | `prod-mk5-heat_sink`          |  4 / 1 | cooling system |
| copper sheet   |    432 | 43,20 &rarr; 48 | `prod-mk5-copper_sheet`       |  4 / 2 | cooling system |
| motor          |     50 | 10 &rarr; 12    | `prod-mk5-motor`              |  2 / 1 | turbo motor    |
| stator         |    100 | 20 &rarr; 21    | `prod-mk5-stator`             |  7 / 1 | turbo motor    |
| copper ingot   |  1 000 | 33,33 &rarr; 48 | `prod-mk5-copper_ingot`       |  3 / 2 | turbo motor    |
| steel pipe     |    300 | 15 &rarr; 24    | `prod-mk5-steel_pipe`         |  2 / 1 | turbo motor    |
| steel ingot    |    450 | 10 &rarr; 12    | `prod-mk5-steel_ingot`        |  2 / 1 | turbo motor    |
| rotor          |    100 | 25 &rarr; 26    | `prod-mk5-rotor`              | 13 / 1 | turbo motor    |
| iron rod       |  1 125 | 75 &rarr; 84    | `prod-mk5-iron_rod`           |  7 / 2 | turbo motor    |
| iron ingot     |  1 125 | 37,50 &rarr; 48 | `prod-mk5-iron_ingot`         |  3 / 2 | turbo motor    |

## Train Stations
|                            |                   |                         |
|----------------------------|-------------------|-------------------------|
| alclad aluminum sheet (in) | coal (in)         | radio control unit (in) |
|                            | nitrogen gas (in) | rubber (in)             |
|                            | nitrogen gas (in) | cooling system          |
|                            | nitrogen gas (in) | turbo motor             |

## Production Floor
|                          |                                 |                                 |                                 |
|--------------------------|---------------------------------|---------------------------------|---------------------------------|
| 1 `prod-mk5-iron_ingot`  | 2 `prod-mk5-iron_ingot`         |                                 |                                 |
| 3 `prod-mk5-iron_rod`    | 4 `prod-mk5-iron_rod`           | 2 `prod-mk5-copper_ingot`       | 1 `prod-mk5-copper_ingot`       |
| 13 `prod-mk5-rotor`      | 2 `prod-mk5-steel_ingot`        | 2 `prod-mk5-copper_sheet`       | 2 `prod-mk5-copper_sheet`       |
| 2 `prod-mk5-motor`       | 7 `prod-mk5-stator`             | 2 `prod-mk5-steel_pipe`         | 4 `prod-mk5-heat_sink`          |
| 4 `prod-mk5-turbo_motor` | 4 `prod-mk5-mk2-cooling_system` | 4 `prod-mk5-mk2-cooling_system` | 4 `prod-mk5-mk2-cooling_system` |

## Balancers
|              |     |
|--------------|-----|
| copper ingot | 2-3 |
| copper ore   | 2-2 |
| iron rod     | 2-2 |
| iron ingot   | 2-2 |
| iron ore     | 2-2 |

## Needed to Build
| blueprints                      | amount |
|---------------------------------|-------:|
| `prod-mk5-turbo_motor`          |      4 |
| `prod-mk5-mk2-cooling_system`   |     12 |
| `prod-mk5-heat_sink`            |      4 |
| `prod-mk5-copper_sheet`         |      4 |
| `prod-mk5-motor`                |      2 |
| `prod-mk5-stator`               |      7 |
| `prod-mk5-copper_ingot`         |      3 |
| `prod-mk5-steel_pipe`           |      2 |
| `prod-mk5-steel_ingot`          |      2 |
| `prod-mk5-rotor`                |     13 |
| `prod-mk5-iron_rod`             |      7 |
| `prod-mk5-iron_ingot`           |      3 |
|                                 |        |
| water extractor                 |      3 |
| train station                   |      3 |
| freight platform                |      6 |
| fluid freight platform          |      3 |
| `fluid-unload-mk2`              |      3 |
| empty platform with catwalk     |      3 |
|                                 |        |
| `prod-floor-empty`              |     24 |
| `prod-floor-4-1`                |      1 |
| `prod-floor-2-2-1-0`            |      3 |
| `prod-floor-2-1`                |      3 |
| `prod-floor-2i-1`               |      2 |
| `prod-floor-1-1`                |      9 |
| `prod-floor-empty`              |     12 |
|                                 |        |
| `prod-floor-corner`             |     40 |
| `prod-floor-corner_pillar`      |     18 |
| `prod-floor-connect`            |     52 |
| `prod-floor-connect_stairs`     |     47 |
|                                 |        |
| `rail-straight-one_wall`        |      4 |
| `rail-curve-branch`             |      2 |
| `rail-straight-one_wall_pillar` |      1 |
