# Alien Matter Factory

| goal                     | amount |  coal | aluminum ingot | alclad aluminum sheet | reanimated SAM | supercomputer | crystal oscillator |
|--------------------------|-------:|------:|---------------:|----------------------:|---------------:|--------------:|-------------------:|
| ficsite trigon           |    540 |       |            720 |                     0 |            360 |             0 |                  0 |
| neural-quantum processor |   4,76 |   952 |          95,20 |                     0 |          47,60 |          4,76 |                  0 |
| superposition oscillator |     20 | 2 400 |              0 |                   180 |             50 |             0 |                 20 |
| time crystal             |     60 | 2 400 |              0 |                     0 |              0 |             0 |                  0 |
| dark matter crystal      |    120 | 2 400 |              0 |                     0 |            300 |             0 |                  0 |

| input                          | amount |
|--------------------------------|-------:|
| alclad aluminum sheet (import) |    180 |
| aluminum ingot (import)        |    720 |
| reanimated SAM (import)        |    360 |
| supercomputer (import)         |   4,76 |
| crystal oscillator (import)    |     20 |
| coal                           |  2 400 |

| product                  | amount | producers     | blueprint                          |  amount | max                      |
|--------------------------|-------:|---------------|------------------------------------|--------:|--------------------------|
| neural-quantum processor |   4,76 | 1,59 &rarr; 2 |                                    | 2 / 1x2 | neural-quantum processor |
| superposition oscillator |     20 | 4 &rarr; 4    |                                    | 4 / 2x2 | superposition oscillator |
| excited photonic matter  |    500 | 2,50 &rarr; 4 | `prod-mk2-excited_photonic_matter` |   2 / 1 | superposition oscillator |
| ficsite trigon           |    540 | 18 &rarr; 24  | `prod-mk5-ficsite_trigon`          |   2 / 1 | ficsite trigon           |
| ficsite ingot            |    180 | 6 &rarr; 6    | `prod-mk5-ficsite_ingot_AI`        |   3 / 1 | ficsite trigon           |
| time crystal             |     60 | 10 &rarr; 10  | `prod-mk5-time_crystal`            |   5 / 1 | time crystal             |
| diamonds                 |    120 | 4 &rarr; 4    | `prod-mk5-diamonds`                |   4 / 4 | time crystal             |
| dark matter crystal      |    120 | 4 &rarr; 4    | `prod-mk5-mk2-dark_matter_crystal` |   4 / 1 | superposition oscillator |
| dark matter residue      |    600 | 6 &rarr; 6    | `prod-mk5-mk2-dark_matter_residue` |   3 / 1 | dark matter crystal      |

## Train Stations
|                          |                         |                            |
|--------------------------|-------------------------|----------------------------|
| neural-quantum processor | supercomputer (in)      | alclad aluminum sheet (in) |
| superposition oscillator | crystal oscillator (in) |                            |
| time crystal             | dark matter crystal     | aluminum ingot (in)        |
| ficsite trigon           |                         | reanimated SAM (in)        |

## Production Floor
|                             |                               |                           |                                      |
|-----------------------------|-------------------------------|---------------------------|--------------------------------------|
| (train)                     | (train)                       | (train)                   | 4 `prod-mk5-mk2-dark_matter_crystal` |
| (train)                     | (train)                       | (train)                   |                                      |
| neural-quantum processor    | superposition oscillator      | superposition oscillator  | 3 `prod-mk5-mk2-dark_matter_residue` |
| neural-quantum processor    | superposition oscillator      | superposition oscillator  | 2 `prod-mk2-excited_photonic_matter` |
| 2 `prod-mk5-ficsite_trigon` | 3 `prod-mk5-ficsite_ingot_AI` | 5 `prod-mk5-time_crystal` |                                      |
| 1 `prod-mk5-diamonds`       | 1 `prod-mk5-diamonds`         | 1 `prod-mk5-diamonds`     | 1 `prod-mk5-diamonds`                |
