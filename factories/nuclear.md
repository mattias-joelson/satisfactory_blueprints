# Nuclear Power Production

| goal                  | amount | iron ore | copper ore | limestone |     coal | water | nitrogen gas | caterium ore | sulfur | raw quartz | uranium | uranium waste | alclad aluminum sheet | fabric | aluminum casing |
|-----------------------|-------:|---------:|-----------:|----------:|---------:|------:|-------------:|-------------:|-------:|-----------:|--------:|--------------:|----------------------:|-------:|----------------:|
| plutonium fuel rod    |   5,25 |   748,15 |        819 |     1 890 |   590,63 |   315 |        1 260 |          378 |    315 |        315 |       0 |          1050 |                262,50 |      0 |               0 |
| uranium fuel rod      |     21 | 1 464,75 |      1 680 |     3 024 | 1 464,75 | 1 260 |            0 |        1 260 |  1 260 |          0 |   2 100 |             0 |                     0 |      0 |               0 |
| iodine-infused filter |     10 |       30 |          0 |         0 |       40 |     0 |            0 |           48 |      0 |          0 |       0 |             0 |                     0 |     20 |              10 |

| input                      |       amount | where                                               |
|----------------------------|-------------:|-----------------------------------------------------|
| *iron ore                  |     2 242,88 | NucSt (2 340)                                       |
| *copper ore                |        2 499 | NucSt (2 340)<br>NucCoCS (480)                      |
| limestone                  | 4 914 (4320) | NucSt (2 160)<br>NucCa (780)<br>NucCoCS (1380)<br>x |
| *coal                      |     2 095,38 | NucSt (2 580)                                       |
| water                      |        1 575 |                                                     |
| *nitrogen gas              |        1 260 | NucNg (1 650)                                       |
| *caterium ore              |        1 686 | NucCa (1 980)                                       |
| *sulfur                    |        1 575 | NucSu (1 680)                                       |
| *raw quartz                |          315 | NucCa (480)                                         |
| uranium                    |        2 100 |                                                     |
| uranium waste              |        1 050 |                                                     |
| alclad aluminum sheet (in) |       262,50 |                                                     |
| *fabric (in)               |           20 | NucSt (20)                                          |
| aluminum casing (in)       |           10 |                                                     |

| product                     |   amount | producers        | blueprint                                                        | amount | where                                 |
|-----------------------------|---------:|------------------|------------------------------------------------------------------|-------:|---------------------------------------|
| plutonium fuel rod          |     5,25 | 21 &rarr; 22     | `pow-mk5-plutonium_fuel_rod`                                     | 11 / 1 |                                       |
| encased plutonium cell      |   157,50 | 31,50 &rarr; 36  | `pow-mk5-encased_plutonium_cell`                                 |  6 / 1 |                                       |
| plutonium pellet            |      315 | 11               |                                                                  |     11 |                                       |
| non-fissile uranium         |    1 050 | 21 &rarr; 21     | `pow-mk5-mk2-non-fissile_uranium`                                | 21 / 2 |                                       |
|                             |          |                  |                                                                  |        |                                       |
| uranium fuel rod            |       21 | 52,50 &rarr; 54  | `pow-mk5-uranium_fuel_rod`                                       | 27 / 2 |                                       |
| encased uranium cell        |    1 050 | 42 &rarr; 42     | `pow-mk5-mk2-encased_uranium_cell`                               | 42 / 3 |                                       |
|                             |          |                  |                                                                  |        |                                       |
| sulfuric acid               |     1575 | 31,50 &rarr; 32  | `prod-mk5-mk2-sulfuric_acid_L`<br>`prod-mk5-mk2-sulfuric_acid_R` |     32 |                                       |
| nitric acid                 |      315 | 10,50 &rarr; 11  | `prod-mk5-mk2-nitric_acid`                                       | 11 / 2 |                                       |
| water                       |     1575 | 13,13 &rarr; 14  |                                                                  |     16 |                                       |
| iodine-infused filter       |       10 | 2,67 &rarr; 3    | `prod-mk5-iodine-infused_filter`                                 |  3 / 1 |                                       |
| gas filter                  |       10 | 1,33 &rarr; 2    | `prod-mk5-gas_filter`                                            |  1 / 1 | Coal                                  |
| iron plate                  |      125 | 6,25 &rarr; 12   | `prod-mk5-iron_plate`                                            |  1 / 1 | Coal                                  |
| iron ingot                  |   187,50 | 6,25 &rarr; 16   | `prod-mk5-iron_ingot`                                            |  1 / 1 | (Coal)                                |
|                             |          |                  |                                                                  |        |                                       |
| silica                      |      525 | 14 &rarr; 24     | `prod-mk5-silica`                                                |  2 / 1 | NucCI                                 |
| heat sink                   |     52,5 | 7 &rarr; 12      | `prod-mk5-heat_sink`                                             |  2 / 1 |                                       |
| electromagnetic control rod |   136,50 | 34,13 &rarr; 36  | `prod-mk5-electromagnetic_control`                               |  6 / 1 |                                       |
| ai limiter                  |   136,50 | 27,3 &rarr; 30   | `prod-mk5-AI_limiter`                                            | 10 / 1 |                                       |
| caterium ingot              |      562 | 37,47 &rarr; 48  | `prod-mk5-caterium_ingot`                                        |  3 / 3 | NucCI                                 |
| copper sheet                |      840 | 84 &rarr; 84     | `prod-mk5-copper_sheet`                                          |  7 / 3 | Coal 760, NucCoCS 240                 |
| stator                      |   204,75 | 40,95 &rarr; 42  | `prod-mk5-stator`                                                | 14 / 2 | Coal                                  |
| copper ingot                |    2 499 | 83,30 &rarr; 112 | `prod-mk5-copper_ingot`                                          |  7 / 4 | Coal                                  |
| steel pipe                  |   614,25 | 30,71 &rarr; 36  | `prod-mk5-steel_pipe`                                            |  3 / 2 | (Coal)                                |
| encased industrial beam     |       63 | 10,5 &rarr; 12   | `prod-mk5-encased_industrial_beam`                               |  2 / 1 |                                       |
| steel beam                  |   283,50 | 18,9 &rarr; 24   | `prod-mk5-steel_beam`                                            |  2 / 2 | Coal                                  |
| steel ingot                 | 2 055,38 | 45,68 &rarr; 54  | `prod-mk5-steel_ingot`                                           | 18 / 3 | (Coal)                                |
| concrete                    |    1 638 | 109,2 &rarr; 156 | `prod-mk5-concrete`                                              | 13 / 7 | Coal 342, NucCI 260, NucCoCS 460, xxx |

## NucSt (Nuclear Steel)
| goal                    | amount | iron ore | copper ore | limestone |   coal | fabric |
|-------------------------|-------:|---------:|-----------:|----------:|-------:|-------:|
| iron plate              |    105 |   157,50 |          0 |         0 |      0 |      0 |
| copper sheet            |    760 |        0 |      1 520 |         0 |      0 |      0 |
| encased industrial beam |     63 |      756 |          0 |     1 134 |    756 |      0 |
| steel beam              |  94,50 |      378 |          0 |         0 |    378 |      0 |
| stator                  | 204,75 |   921,38 |        819 |         0 | 921,38 |      0 |
| concrete                |    342 |        0 |          0 |     1 026 |      0 |      0 |
| gas filter              |     10 |       30 |          0 |         0 |     40 |     20 |

| input       |   amount |
|-------------|---------:|
| iron ore    | 2 242,88 |
| copper ore  |     2339 |
| limestone   |     2160 |
| coal        | 2 095,38 |
| fabric (in) |       20 |

| product                 |   amount | producers       | blueprint                          | amount |
|-------------------------|---------:|-----------------|------------------------------------|-------:|
| encased industrial beam |       63 | 10,50 &rarr; 12 | `prod-mk5-encased_industrial_beam` |  2 / 1 |
| concrete                |      720 | 48 &rarr; 72    | `prod-mk5-concrete`                |  6 / 3 |
| copper sheet            |      760 | 76 &rarr; 96    | `prod-mk5-copper_sheet`            |  8 / 2 |
| stator                  |   204,75 | 40,95 &rarr; 42 | `prod-mk5-stator`                  | 14 / 2 |
| copper ingot            |    2 339 | 77,97 &rarr; 96 | `prod-mk5-copper_ingot`            |  6 / 3 |
| gas filter              |       10 | 1,33 &rarr; 2   | `prod-mk5-gas_filter`              |  1 / 1 |
| iron plate              |      125 | 6,25 &rarr; 12  | `prod-mk5-iron_plate`              |  1 / 1 |
| iron ingot              |   187,50 | 6,25 &rarr; 16  | `prod-mk5-iron_ingot`              |  1 / 1 |
| steel beam              |   283,50 | 18,9 &rarr; 24  | `prod-mk5-steel_beam`              |  2 / 2 |
| steel pipe              |   614,25 | 30,71 &rarr; 36 | `prod-mk5-steel_pipe`              |  3 / 2 |
| steel ingot             | 2 055,38 | 45,68 &rarr; 54 | `prod-mk5-steel_ingot`             |  9 / 3 |

### Train Stations
|                         |               |         |
|-------------------------|---------------|---------|
| encased industrial beam | (fabric (in)) | (coal)  |
| steel beam              | copper sheet  | (coal)  |
| stator                  | iron plate    | (empty) |
| concrete                | gas filter    | (empty) |

###  Production Floor
|                                      |                          |                          |                           |                           |                           |
|--------------------------------------|--------------------------|--------------------------|---------------------------|---------------------------|---------------------------|
|                                      | **train**                | **train**                | **train**                 | **train**                 |                           |
|                                      | **train**                | **train**                | **train**                 | **train**                 | 2 `prod-mk5-concrete`     |
| 2 `prod-mk5-concrete`                | **train**                | **train**                | **train**                 | **train**                 | 1 `prod-mk5-gas_filter`   |
| 2 `prod-mk5-concrete`                | **train**                | **train**                | **train**                 | **train**                 | 1 `prod-mk5-iron_plate`   |
| 2 `prod-mk5-encased_industrial_beam` | **train**                | **train**                | **train**                 | **train**                 | 1 `prod-mk5-iron_ingot`   |
| 1 `prod-mk5-steel_beam`              | **train**                | **train**                | **train**                 | **train**                 | 4 `prod-mk5-copper_sheet` |
| 1 `prod-mk5-steel_beam`              | 1 `prod-mk5-steel_pipe`  | 2 `prod-mk5-steel_pipe`  | 7 `prod-mk5-stator`       | 7 `prod-mk5-stator`       | 4 `prod-mk5-copper_sheet` |
| 3 `prod-mk5-steel_ingot`             | 3 `prod-mk5-steel_ingot` | 3 `prod-mk5-steel_ingot` | 2 `prod-mk5-copper_ingot` | 2 `prod-mk5-copper_ingot` | 2 `prod-mk5-copper_ingot` |

### Needed to Build
| blueprints                         | amount |
|------------------------------------|-------:|
| `prod-mk5-encased_industrial_beam` |      2 |
| `prod-mk5-concrete`                |      6 |
| `prod-mk5-copper_sheet`            |      8 |
| `prod-mk5-stator`                  |     14 |
| `prod-mk5-copper_ingot`            |      6 |
| `prod-mk5-gas_filter`              |      1 |
| `prod-mk5-iron_plate`              |      1 |
| `prod-mk5-iron_ingot`              |      1 |
| `prod-mk5-steel_beam`              |      2 |
| `prod-mk5-steel_pipe`              |      3 |
| `prod-mk5-steel_ingot`             |      9 |

## NucCa (Nuclear Caterium Ingot)
| goal           | amount | limestone | caterium ore | raw quartz |
|----------------|-------:|----------:|-------------:|-----------:|
| concrete       |    260 |       780 |            0 |          0 |
| caterium ingot |    660 |         0 |        1 980 |          0 |
| silica         |    780 |         0 |            0 |        468 |

| input        | amount |
|--------------|-------:|
| limestone    |    780 |
| caterium ore |  1 980 |
| raw quartz   |    468 |

| product        | amount | producers       | blueprint                 | amount |
|----------------|-------:|-----------------|---------------------------|-------:|
| concrete       |    260 | 17,33 &rarr; 24 | `prod-mk5-concrete`       |  2 / 1 |
| caterium ingot |    660 | 44 &rarr; 48    | `prod-mk5-caterium_ingot` |  3 / 3 |
| silica         |    780 | 20,80 &rarr; 24 | `prod-mk5-silica`         |  2 / 1 |

### Train Station
|                |
|----------------|
| concrete       |
| caterium ingot |
| silica         |
| (empty)        |

### Production Floor
|                             |                             |                             |                       |
|-----------------------------|-----------------------------|-----------------------------|-----------------------|
| 2 `prod-mk5-silica`         | `logi-balancer-4_4_mk5`     |                             |                       |
| 1 `prod-mk5-caterium_ingot` | 1 `prod-mk5-caterium_ingot` | 1 `prod-mk5-caterium_ingot` | 2 `prod-mk5-concrete` |

## NucCoCS (Nuclear Concrete Copper Sheet)
| goal         | amount | copper ore | limestone |
|--------------|-------:|-----------:|----------:|
| concrete     |    460 |          0 |     1 380 |
| copper sheet |    240 |        480 |         0 |

| input      | amount |
|------------|-------:|
| limestone  |   1380 |
| copper ore |    480 |

| product      | amount | producers       | blueprint               | amount |
|--------------|-------:|-----------------|-------------------------|-------:|
| concrete     |    460 | 30,67 &rarr; 48 | `prod-mk5-concrete`     |  4 / 2 |
| copper sheet |    240 | 24 &rarr; 24    | `prod-mk3-copper_sheet` |  2 / 1 |
| copper ingot |    480 | 16 &rarr; 16    | `prod-mk3-copper_ingot` |  1 / 1 |

### Train Station
|              |
|--------------|
| (empty)      |
| (empty)      |
| concrete     |
| copper sheet |

### Production Floor
|                       |                           |                           |                       |
|-----------------------|---------------------------|---------------------------|-----------------------|
| 2 `prod-mk5-concrete` | 2 `prod-mk3-copper_sheet` | 1 `prod-mk3-copper_ingot` | 2 `prod-mk5-concrete` |

## NucNG (Nuclear Nitrogen Gas)
| goal         | amount |
|--------------|-------:|
| nitrogen gas |  1 650 |

| input        | amount |
|--------------|-------:|
| nitrogen gas |  1 650 |

### Train Station
|                  |
|------------------|
| nitrogen gas     |
| nitrogen gas     |
| nitrogen gas     |
| (reanimated SAM) |

## NucSu (Nuclear Sulfur)
| goal   | amount |
|--------|-------:|
| sulfur |  1 680 |

| input  | amount |
|--------|-------:|
| sulfur |  1 680 |

### Train Station
|         |
|---------|
| sulfur  |
| sulfur  |
| sulfur  |
| (empty) |

## NucNF (Nuclear Non-Fissile)
| goal                        | amount | limestone | alclad aluminum sheet | copper sheet | stator | caterium ingot | aluminum casing | gas filter |
|-----------------------------|-------:|----------:|----------------------:|-------------:|-------:|---------------:|----------------:|-----------:|
| concrete                    |    200 |       600 |                     0 |            0 |      0 |              0 |               0 |          0 |
| heat sink                   |   52,5 |         0 |                262,50 |       157,50 |      0 |              0 |               0 |          0 |
| electromagnetic control rod |  136,5 |         0 |                     0 |       682,50 | 204,75 |            546 |               0 |          0 |
| iodine-infused filter       |     10 |         0 |                     0 |            0 |      0 |             16 |              10 |         10 |

| input                      | amount |
|----------------------------|-------:|
| limestone                  |    600 |
| copper sheet (in)          |    840 |
| stator (in)                | 204,75 |
| alclad aluminum sheet (in) | 262,50 |
| aluminum casing (in)       |     10 |
| gas filter (in)            |     10 |

| product                     | amount | producers       | blueprint                          | amount |
|-----------------------------|-------:|-----------------|------------------------------------|-------:|
| concrete                    |    200 | 13,33 &rarr; 24 | `prod-mk5-concrete`                |  2 / 1 |
| heat sink                   |  52,50 | 7 &rarr; 12     | `prod-mk5-heat_sink`               |  2 / 1 |
| electromagnetic control rod | 136,50 | 34,13 &rarr; 36 | `prod-mk5-electromagnetic_control` |  6 / 1 |
| AI limiter                  | 136,50 | 27,30 &rarr; 30 | `prod-mk5-AI_limiter`              | 10 / 1 |
| iodine-infused filter       |     10 | 2,667 &rarr; 3  | `prod-mk5-iodine-infused_filter`   |  3 / 1 |

### Train Stations

|                            |                     |                             |
|----------------------------|---------------------|-----------------------------|
| alclad aluminum sheet (in) |                     | electromagnetic control rod |
| aluminum casing (in)       | caterium ingot (in) | heat sink                   |
| copper sheet (in)          | stator (in)         | concrete                    |
| gas filter (in)            | copper sheet (in)   |                             |

### Production Floor
| |                                    |                       |                        |                          |                                       |
|-|------------------------------------|-----------------------|------------------------|--------------------------|---------------------------------------|
| | 3 `prod-mk5-iodine-infused_filter` | 2 `prod-mk5-concrete` | 2 `prod-mk5-heat_sink` | 10 `prod-mk5-AI_limiter` | 12 `prod-mk5-electromagnetic_control` |

## NucRA (Nuclear Radio Active)
| goal               | amount | water | uranium | sulfur | concrete | encased industrial beam | electromagnetic control rod | uranium waste | nitrogen gas | steel beam | heat sink | silica |
|--------------------|-------:|------:|--------:|-------:|---------:|------------------------:|----------------------------:|--------------:|-------------:|-----------:|----------:|-------:|
| plutonium fuel rod |   5,25 |   315 |       0 |    315 |      630 |                       0 |                       31,50 |         1 050 |        1 260 |      94,50 |     52,50 |    525 |
| uranium fuel rod   |     21 | 1 260 |   2 100 |  1 260 |      630 |                      63 |                         105 |             0 |            0 |          0 |         0 |      0 |

| input                            | amount |
|----------------------------------|-------:|
| water                            |  1 575 |
| uranium                          |  2 100 |
| sulfur                           |  1 575 |
| concrete (in)                    |  1 260 |
| encased industrial beam (in)     |     63 |
| electromagnetic control rod (in) | 136,50 |
| uranium waste (in)               |  1 050 |
| nitrogen gas (in)                |  1 260 |
| steel beam (in)                  |  94,50 |
| heat sink (in)                   |  52,50 |
| silica (in)                      |    525 |

| product                | amount | producers       | blueprint                                                        | amount |
|------------------------|-------:|-----------------|------------------------------------------------------------------|-------:|
| plutonium fuel rod     |   5,25 | 21 &rarr; 22    | `pow-mk5-plutonium_fuel_rod`                                     | 11 / 1 |
| encased plutonium cell | 157,50 | 31,50 &rarr; 36 | `pow-mk5-encased_plutonium_cell`                                 |  6 / 1 |
| plutonium pellet       |    315 | 11              |                                                                  | 11 (2) |
| non-fissile uranium    |  1 050 | 21 &rarr; 21    | `pow-mk5-mk2-non-fissile_uranium`                                | 21 / 2 |
|                        |        |                 |                                                                  |        |
| uranium fuel rod       |     21 | 52,50 &rarr; 54 | `pow-mk5-uranium_fuel_rod`                                       | 27 / 2 |
| encased uranium cell   |  1 050 | 42 &rarr; 42    | `pow-mk5-mk2-encased_uranium_cell`                               | 42 / 4 |
|                        |        |                 |                                                                  |        |
| sulfuric acid          |   1575 | 31,50 &rarr; 33 | `prod-mk5-mk2-sulfuric_acid_L`<br>`prod-mk5-mk2-sulfuric_acid_R` | 26 + 7 |
| nitric acid            |    315 | 10,50 &rarr; 11 | `prod-mk5-mk2-nitric_acid`                                       | 11 / 3 |
| water                  |   1575 | 13,13 &rarr; 14 |                                                                  |     14 |

### Balancers
- sulfur 4-4
- uranium 4-4
- uranium waste 2-3
- concrete 4-2 
- encased uranium cell 2-2

### Train Stations
| pu + ur                 | pu         | pu + ur                     | ur      | pu + ur | pu           |
|-------------------------|------------|-----------------------------|---------|---------|--------------|
| encased industrial beam | concrete   | concrete                    | uranium | sulfur  | nitrogen gas |
| steel beam              | iron plate | heat sink                   | uranium | sulfur  | nitrogen gas |
| concrete                | silica     | electromagnetic control rod | uranium | sulfur  | nitrogen gas |
| concrete                |            |                             | uranium |         |              |

| pu           | pu         | pu+ur                        | pu+ur                   | pu+ur  | ur      |
|--------------|------------|------------------------------|-------------------------|--------|---------|
| nitrogen gas | concrete   | electromagnetic control rodd | encased industrial beam | sulfur | uranium |
| nitrogen gas | iron plate | heat sink                    | steel beam              | sulfur | uranium |
| nitrogen gas | silica     | concrete                     | concrete                | sulfur | uranium |
|              |            |                              | concrete                | sulfur | uranium |

### Production Floor
| |    |     |     |     | | train |              |            |             |     |     |    | 
|-|----|-----|-----|-----|-|-------|--------------|------------|-------------|-----|-----|----|
| |    | epc | pfu |     | |       |              |            | ufr         | ufr |     |    |
| | pp | pp  | nfu | nfu | |       |              | euc        | euc         | euc | euc |    |
| |    | na  | na  | na  | |       | sa           | sa         | sa          | sa  | sa  | sa |
| |    | sa  | sa  | sa  | |       | 4-4 concrete | 4-4 sulfur | 4-4 uranium | sa  | sa  | sa |
| |    |     |     |     | |       |              |            |             |     |     |    |


### Plants
21 uranium fuel rods/min * 5 min burn time &rarr; 105 plants. That is 15 plants per 300 mined uranium.
5,25 plutonium fuel rod/min * 10 min burn time &rarr; 52,5 plants. That is 17,5 plants per 300 mined uranium.
