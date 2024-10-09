# Oil Refinery

| production (either) | amount |
|---------------------|-------:|
| plastic             |    800 |
| rubber              |    800 |
| black powder        |    180 |
| smokeless powder    |    200 |
| fabric              |    300 |
| turbofuel           | 666,67 |

| input     | amount |
|-----------|-------:|
| crude oil |   1200 |
| coal      | 533,33 |
| sulfur    | 533,33 |
| water     |    600 |

## Plastic, Rubber and Powders

| product          | amount | producers   | blueprint                                                                | amount |
|------------------|-------:|-------------|--------------------------------------------------------------------------|-------:|
| plastic          |    800 | 40 -> 40    | `prod-mk5-mk2-plastic_LR`<br>`prod-mk5-mk2-plastic_RL`                   |     14 |
| rubber           |    800 | 40 -> 40    | `prod-mk5-mk2-rubber_LR`<br>`prod-mk5-mk2-rubber_RL`                     |     14 |
| black powder     |    180 | 6 -> 6      | `prod-mk5-black_powder`                                                  |      1 |
| smokeless powder |    200 | 10 -> 10    | `prod-mk5-mk2-smokeless_powder_LR`<br>`prod-mk5-mk2-smokeless_powder_RL` |      4 |
| fuel             | 533,33 | 13,33 -> 14 | `pow-mk2-residual_fuel`                                                  |      5 |
| compacted coal   | 355,55 | 14,22 -> 18 | `pow-mk5-compacted_coal`                                                 |      3 |
| turbofuel        | 444,44 | 23,70 -> 24 | `pow-mk5-mk2-turbofuel_L`<br>`pow-mk5-mk2-turbofuel_R`                   |      8 |
| fuel generator   |        | 59,25 -> 60 | `pow-fuel_generator`<br>`pow-fuel_generator_junction` (half amount)      |     60 |

# Turbofuel and Fabric

| product        | amount | producers    | blueprint                                                                | amount |
|----------------|-------:|--------------|--------------------------------------------------------------------------|-------:|
| fuel           |    800 | 20 -> 20     | `pow-mk5-mk2-fuel_L`<br>`pow-mk5-mk2-fuel_R`                             |      7 |
| fabric         |    300 | 10 -> 10     | `prod-mk5-mk2-polyester_fabric_LR`<br>`prod-mk5-mk2-polyester_fabric_RL` |      4 |
| plastic        |    200 | 10 -> 10     | `prod-mk5-mk2-residual_plastic_LR`<br>`prod-mk5-mk2-residual_plastic_RL` |      4 |
| empty canister |    400 | 6,67 -> 12   | `prod-mk5-empty_canister`                                                |      1 |
| packaged water |    400 | 6,67 -> 8    | `prod-mk5-mk2-packaged_water_LR`<br>`prod-mk5-mk2-packaged_water_RL`     |      2 |
| compacted coal | 533,33 | 21,33 -> 24  | `pow-mk5-compacted_coal`                                                 |      4 |
| turbofuel      | 666,67 | 35,56 -> 36  | `pow-mk5-mk2-turbofuel_L`<br>`pow-mk5-mk2-turbofuel_R`                   |     12 |
| fuel generator |        | 88,89 -> 100 | `pow-fuel_generator`<br>`pow-fuel_generator_junction` (half amount)      |    100 |
