# satisfactory_blueprints
Blueprints for Satisfactory game.

## Production Factories

Ground level of factory consist of the production floor and the basement. Factory modules are placed on the production
floor and the interconnection between them are handled on the basement floor.

### Parts

### Production Floor Grid

| blueprint                          | floors             | electric connection | pillar top with sockets | used for                                                                               |
|------------------------------------|--------------------|---------------------|-------------------------|----------------------------------------------------------------------------------------|
| `prod-floor-corner`                | :white_check_mark: |                     |                         | Corners of module floors.                                                              |
| `prod-floor-corner_pillar`         | :white_check_mark: | :white_check_mark:  | :white_check_mark:      | Corner of module floors, connect electricity on basement floor and underneath factory. |
| `prod-floor-connect`               | :white_check_mark: |                     |                         | Between module floors.                                                                 |
| `prod-floor-connect_stairs`        | :white_check_mark: |                     |                         | Between module floors. Stairs between production floor and basement.                   |
| `prod-floor-connect_stairwell`     | :white_check_mark: |                     |                         | Between module floors. Stairs between production floor, basement and below.            |
|                                    |                    |                     |                         |                                                                                        |
| `prod-floor-corner_outside`        |                    |                     |                         | Decoration outside of factory floor corners.                                           |
| `prod-floor-corner_pillar_outside` |                    |                     |                         | Decoration outside of factory floor corners (for pillars).                             |
| `prod-floor-connect_outside`       |                    |                     |                         | Decoration outside of factory floor connections.                                       |

Uses parts from
- HUB Upgrade 2 (power line)
- HUB Upgrade 3 (power pole)
- Tier 1 - Base Building (foundation, ramp, wall)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet, double wall outlet)
- AWESOME Shop - Foundations - Half Foundation Set (half foundation)
- AWESOME Shop - Foundations - Inverted Ramp Set (inverted ramp)
- AWESOME Shop - Architecture - Modern Railing (modern railing)
- AWESOME Shop - Architecture - Modern Catwalks (catwalks)
- AWESOME Shop - Customizer - Concrete Foundation Material
- AWESOME Shop - Customizer - Concrete Wall Material

### Module Production Floor

Two layers of 4m foundation, 8++ m vertical in between. Wall outlet under the top layer in the corners, connect with cables.

| parts blueprint               | notes |
|-------------------------------|-------|
| `prod-parts-production_floor` |       |

| blueprint                   | input holes | intermediate input hole | input pipe holes | output hole        | output pipe hole   | used for                                                                                               |
|-----------------------------|------------:|-------------------------|-----------------:|--------------------|--------------------|--------------------------------------------------------------------------------------------------------|
| `prod-floor-empty`          |             |                         |                  |                    |                    | no wiring, used for non-electric modules (train stations, mall)                                        |
| `prod-floor-1-1`            |           1 |                         |                  | :white_check_mark: |                    | for one-ingredient parts (smelter, constructor)                                                        |
| `prod-floor-2-1`            |           2 |                         |                  | :white_check_mark: |                    | for two-ingredient parts (foundry, assembler)                                                          |
| `prod-floor-2i-1`           |           2 | :white_check_mark:      |                  | :white_check_mark: |                    | for two-ingredient parts where one intermediate is manufactured locally (example: rotors using screws) |
| `prod-floor-3-1`            |           3 |                         |                  | :white_check_mark: |                    | for three-ingredient parts (manufacturer)                                                              |
| `prod-floor-3i-1`           |           3 | :white_check_mark:      |                  | :white_check_mark: |                    | for three-ingredient parts where one intermediate is manufactured locally (manufacturer)               |
| `prod-floor-4-1`            |           4 |                         |                  | :white_check_mark: |                    | for four-ingredient parts (manufacturer)                                                               |
| `prod-floor-4i-1`           |           4 | :white_check_mark:      |                  | :white_check_mark: |                    | for four-ingredient parts where one intermediate is manufactured locally (manufacturer)                |
| 2-2-1-1                     |           2 |                         |                2 | :white_check_mark: | :white_check_mark: | for blender                                                                                            |
| `prod-floor-storage`        |          18 |                         |                  |                    |                    | for `prod-module-storage`                                                                              |

Uses parts from
- Tier 0 - HUB Upgrade 2 (power line)
- Tier 1 - Base Building (foundation, ramp, wall)
- AWESOME Shop - Management - Conveyor Lift Floor Hole (conveyor lift floor hole)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet)
- AWESOME Shop - Customizer - Concrete Foundation Material

### Module
- `prod-module-stairs` - catwalk stairs between modules
- `prod-module-stairs_top` - catwalk stairs between modules, top floor
- `prod-module-stairs_outside` - catwalk stairs between modules, outermost
- `prod-module-stairs_outside_top` - catwalk stairs between modules, outermost, top floor
- `prod-module-storage` - 18 storage containers


## Production mk3

| template blueprint         | module production floor | notes           |
|----------------------------|-------------------------|-----------------|
| `prod-mk3-smelter`         | `prod-floor-1-1`        | 16 smelters     |
| `prod-mk3-foundry`         | `prod-floor-2-1`        | 6 foundry       |
| `prod-mk3-constructor`     | `prod-floor-1-1`        | 12 constructors |
| `prod-mk3-assembler`       | `prod-floor-2-1`        | 6 assemblers    |
| `prod-mk3-manufacturer`    | `prod-floor-4-1`        | 2 manufacturer  |
| `prod-mk3-manufacturer_3`  | `prod-floor-3-1`        | 2 manufacturer  |
| `prod-mk3-mk1-refinery_LR` | `prod-floor-empty`      | 3 refinery      |
| `prod-mk3-mk1-refinery_RL` | `prod-floor-empty`      | 3 refinery      |
| `prod-mk3-mk2-refinery_LR` | `prod-floor-empty`      | 3 refinery      |
| `prod-mk3-mk2-refinery_RL` | `prod-floor-empty`      | 3 refinery      |

Uses parts from
- Tier 0 - HUB Upgrade 2 (power line, smelter)
- Tier 0 - HUB Upgrade 3 (constructor, power pole)
- Tier 0 - HUB Upgrade 4 (conveyor belt mk1)
- Tier 1 - Base Building (foundation, ramp, wall)
- Tier 1 - Logistics (conveyor lift mk1, splitter, merger)
- Tier 2 - Part Assembly (assembler)
- Tier 3 - Coal Power (pipeline mk1, pipeline junction)
- Tier 3 - Basic Steel Production (foundry)
- Tier 4 - Logistics Mk.3 (conveyor belt mk3, conveyor lift mk3, stackable pipeline support)
- Tier 5 - Oil Processing (refinery)
- Tier 6 - Industrial Manufacturing (manufacturer)
- Tier 6 - Pipeline Engineering (pipeline mk2)
- AWESOME Shop - Management - Conveyor Lift Floor Hole (conveyor lift floor hole)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet)
- AWESOME Shop - Walls - Door Walls (side door wall)
- AWESOME Shop - Customizer - Concrete Foundation Material
- AWESOME Shop - Customizer - Concrete Wall Material

### Smelter mk3
- `prod-mk3-iron_ingot`
- `prod-mk3-copper_ingot`

### Foundry mk3
- `prod-mk3-steel_ingot`

### Constructor mk3
- `prod-mk3-iron_plate`
- `prod-mk3-iron_rod`
- `prod-mk3-cable` (with potential first floor `prod-mk3-cable-wire`, intermediate wire)
- `prod-mk3-copper_sheet`
- `prod-mk3-concrete`
- `prod-mk3-steel_beam`
- `prod-mk3-steal_rod`
- `prod-mk3-reanimated_SAM`

### Assembler mk3
- `prod-mk3-reinforced_iron_plate` (intermediate screws)
- `prod-mk3-rotor` (intermediate screws)
- `prod-mk3-modular_frame`
- `prod-mk3-encased_industrial_beam`
- `prod-mk3-stator` (intermediate wire)
- `prod-mk3-motor`
- `prod-mk3-circuit_board`
- `prod-mk3-black_powder`
- `prod-mk3-nobelisk`
- `prod-mk3-rifle_ammo`
- `prod-mk3-smart_plating`
- `prod-mk3-versatile_framework`
- `prod-mk3-automated_wiring`

### Manufacturer mk3
- `prod-mk3-heavy_modular_frame`
- `prod-mk3-computer`
- `prod-mk3-SAM_fluctuator`
- `prod-mk3-modular_engine`
- `prod-mk3-adaptive_control_unit`

### Refinery mk3
- `prod-mk3-mk1-plastic_L`
- `prod-mk3-mk2-plastic_L`
- `prod-mk3-mk1-plastic_R`
- `prod-mk3-mk2-plastic_R`
- `prod-mk3-mk1-rubber_L`
- `prod-mk3-mk2-rubber_L`
- `prod-mk3-mk1-rubber_R`
- `prod-mk3-mk2-rubber_R`
- `prod-mk3-mk2-smokeless_powder_LR`
- `prod-mk3-mk2-smokeless_powder_RL`
- `prod-mk3-mk1-alumina_solution_LR`
- `prod-mk3-mk1-aluminum_scrap_LR`

## Production mk5

| template blueprint         | module production floor | notes           |
|----------------------------|-------------------------|-----------------|
| `prod-mk5-smelter`         | `prod-floor-1-1`        | 16 smelters     |
| `prod-mk5-foundry`         | `prod-floor-2-1`        | 6 foundry       |
| `prod-mk5-constructor`     | `prod-floor-1-1`        | 12 constructors |
| `prod-mk5-assembler`       | `prod-floor-2-1`        | 6 assemblers    |
| `prod-mk5-manufacturer`    | `prod-floor-4-1`        | 2 manufacturer  |
| `prod-mk5-manufacturer_3`  | `prod-floor-3-1`        | 2 manufacturer  |
| `prod-mk5-mk2-refinery_LR` | `prod-floor-empty`      | 3 refinery      |
| `prod-mk5-mk2-refinery_RL` | `prod-floor-empty`      | 3 refinery      |
| `prod-mk5-mk2-packager_LR` | `prod-floor-empty`      | 4 packager      |
| `prod-mk5-mk2-packager_RL` | `prod-floor-empty`      | 4 packager      |
| blender                    |                         | 1 blender       |

Uses parts from
- Tier 0 - HUB Upgrade 2 (power line, smelter)
- Tier 0 - HUB Upgrade 3 (constructor, power pole)
- Tier 0 - HUB Upgrade 4 (conveyor belt mk1)
- Tier 1 - Base Building (foundation, ramp, wall)
- Tier 1 - Logistics (conveyor lift mk1, splitter, merger)
- Tier 2 - Part Assembly (assembler)
- Tier 3 - Coal Power (pipeline mk1, pipeline junction)
- Tier 3 - Basic Steel Production (foundry)
- Tier 4 - Logistics Mk.3 (stackable pipeline support)
- Tier 5 - Oil Processing (refinery)
- Tier 5 - Fluid Packaging (packager)
- Tier 6 - Industrial Manufacturing (manufacturer)
- Tier 6 - Pipeline Engineering (pipeline mk2)
- Tier 7 - Logistics Mk.5 (conveyor belt mk5, conveyor lift mk5)
- ? (blender)
- AWESOME Shop - Management - Conveyor Lift Floor Hole (conveyor lift floor hole)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet)
- AWESOME Shop - Walls - Door Walls (side door wall)
- AWESOME Shop - Customizer - Concrete Foundation Material
- AWESOME Shop - Customizer - Concrete Wall Material

### Smelter mk5
- `prod-mk5-iron_ingot`
- `prod-mk5-copper_ingot`
- `prod-mk5-caterium_ingot`

### Foundry mk5
- `prod-mk5-aluminum_ingot`
- `prod-mk5-aluminum_ingot_top`

### Constructor mk5
- `prod-mk5-iron_plate`
- `prod-mk5-iron_rod`
- `prod-mk5-cable`
- `prod-mk5-copper_sheet`
- `prod-mk5-concrete`
- `prod-mk5-empty_canister`
- `prod-mk5-aluminum_casing`
- `prod-mk5-quickwire`
- `prod-mk5-quartz_crystal`
- `prod-mk5-silica`

### Assembler mk5
- `prod-mk5-reinforced_iron_plate`
- `prod-mk5-circuit_board`
- `prod-mk5-alclad_aluminum_sheet`
- `prod-mk5-AI_limiter`
- `prod-mk5-black_powder`

### Manufacturer mk5
- `prod-mk5-computer`
- `prod-mk5-supercomputer`
- `prod-mk5-radio_control_unit`
- `prod-mk5-high-speed_connector`
- `prod-mk5-crystal_oscillator`

### Refinery mk5
- `prod-mk5-mk2-plastic_L`
- `prod-mk5-mk2-plastic_R`
- `prod-mk5-mk2-rubber_L`
- `prod-mk5-mk2-rubber_R`
- `prod-mk5-mk2-residual_plastic_LR`
- `prod-mk5-mk2-residual_plastic_RL`
- `prod-mk5-mk1-alumina_solution_LR`
- `prod-mk5-mk1-alumina_solution_RL`
- `prod-mk5-mk1-aluminum_scrap_LR`
- `prod-mk5-mk1-aluminum_scrap_RL`
- `prod-mk5-mk2-polyester_fabric_LR`
- `prod-mk5-mk2-polyester_fabric_RL`
- `prod-mk5-mk2-smokeless_powder_LR`
- `prod-mk5-mk2-smokeless_powder_RL`

### Packager mk5
- `prod-mk5-mk2-packaged_water_LR`
- `prod-mk5-mk2-packaged_water_RL`

### Blender mk5

## Logistics

### Parts
- logi-parts-vertical_splitter_mk2
- logi-parts-vertical_splitter_mk3
- logi-parts-vertical_splitter_mk5
- logi-parts-vertical_merger_mk2
- logi-parts-vertical_merger_mk3
- logi-parts-vertical_merger_mk5

### Balancer mk3
- logi-balancer-2_2_mk3
- logi-balancer-2_2_mk3_high
- logi-balancer-2_3_mk3
- logi-balancer-2_4_mk3
- logi-balancer-3_3_mk3
- logi-balancer-4_4_mk3

### Balancer mk5
- logi-balancer-2_2_mk5
- `logi-balancer-2_2_mk5_high`
- logi-balancer-2_3_mk5
- logi-balancer-2_4_mk5
- logi-balancer-3_3_mk5
- `logi-balancer-4_4_mk5`

## Fluid

### Pumps
- `fluid-pump-mk1-vertical-1`
- `fluid-pump-mk1-mk1-vertical_2x1`
- `fluid-pump-mk1-vertical-2`
- `fluid-pump-mk1-mk1-vertical_2x2`
- `fluid-pump-mk2-vertical-1`
- `fluid-pump-mk2-vertical-2`

### Control - Priority Junction
- fluid-ctrl-prio_junction-mk1-L-L
- fluid-ctrl-prio_junction-mk1-L-R
- fluid-ctrl-prio_junction-mk1-R-L
- fluid-ctrl-prio_junction-mk1-R-R
- fluid-ctrl-prio_junction-mk2-L-L
- fluid-ctrl-prio_junction-mk2-L-R
- fluid-ctrl-prio_junction-mk2-R-L
- fluid-ctrl-prio_junction-mk2-R-R

### Control - Overflow Junction
- fluid-ctrl-overflow_junction-mk1
- fluid-ctrl-3_junction_mk1

### Station
- fluid-load-mk1
- fluid-load-mk2
- fluid-unload-mk1
- fluid-unload-mk2


### Buffer
- fluid-buffer-mk1 - 4 fluid buffer, pipes mk1 (300)
- fluid-buffer-mk2 - 4 fluid buffer, pipes mk2 (600)

## Railway System

All railway blueprints are 3 x 3 foundations using concrete only. Blueprints with electric connection should be
connected with cable so that the pillar sockets provide electricity.

| blueprint                         | walled foundation  | railway            | block signals      | electric connection | pillar top with sockets | used for                                                                                  |
|-----------------------------------|--------------------|--------------------|--------------------|---------------------|-------------------------|-------------------------------------------------------------------------------------------|
| `rail-straight`                   | :white_check_mark: |                    |                    |                     |                         | Straight blocks.                                                                          |
| `rail-straight-block_pillar`      | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:  | :white_check_mark:      | Straight blocks, every fourth blueprint.                                                  |
| `rail-straight-block_temp_pillar` | :white_check_mark: | :white_check_mark: |                    | :white_check_mark:  | :white_check_mark:      | Straight blocks, every fourth blueprint. NOTE! Placeholder for block signals.             |
| `rail-straight-no_wall`           | :white_check_mark: |                    |                    |                     |                         | Double sided stations.                                                                    |
| `rail-straight-no_wall_pillar`    | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Double sided stations.                                                                    |
| `rail-straight-one_wall`          | :white_check_mark: |                    |                    |                     |                         | Single sided stations.                                                                    |
| `rail-straight-one_wall_pillar`   | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Single sided stations.                                                                    |
|                                   |                    |                    |                    |                     |                         |                                                                                           |
| `rail-entry_pillar`               | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Pillar support where signaling is done by hand (instead of `rail-straight-block_pillar`). |
| `rail-curve-branch`               | :white_check_mark: | :white_check_mark: |                    |                     |                         | Curve block, single sided stations.                                                       |
| `rail-curve-back`                 | :white_check_mark: |                    |                    | :white_check_mark:  |                         | Curve block.                                                                              |
| `rail-curve-corner`               | :white_check_mark: |                    |                    |                     |                         | Curve and junction block.                                                                 |
| `rail-junc-branch`                | :white_check_mark: | :white_check_mark: |                    |                     |                         | Junction block, double sided stations.                                                    |
| `rail-junc-back`                  | :white_check_mark: |                    |                    | :white_check_mark:  |                         | Junction block.                                                                           |
|                                   |                    |                    |                    |                     |                         |                                                                                           |
| `rail-slope-1st`                  | :white_check_mark: | :white_check_mark: |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-2nd`                  | :white_check_mark: |                    |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-3rd`                  | :white_check_mark: | :white_check_mark: |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-adjuster`             |                    |                    |                    |                     |                         | For placing parts of slope blocks.                                                        |
| `rail-slope-adjuster_large`       |                    |                    |                    |                     |                         | For placing parts of slope blocks.                                                        |

Uses parts from
- Tier 0 - HUB Upgrade 2 (power line)
- Tier 0 - HUB Upgrade 3 (power pole)
- Tier 1 - Base Building (foundation, ramp, wall)
- Tier 6 - Monorail Train Technology (railway, block signal)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet, double wall outlet)
- AWESOME Shop - Foundations - Double Ramp Set (double ramp)
- AWESOME Shop - Foundations - Inverted Ramp Set (inverted ramp)
- AWESOME Shop - Foundations - Inverted Corner Ramp Pack (inverted up corner, inverted down corner)
- AWESOME Shop - Walls - Inverted Ramp Wall Bundle (inverted ramp wall)
- AWESOME Shop - Walls - Ramp Wall Bundle (ramp wall)
- AWESOME Shop - Customizer - Concrete Foundation Material
- AWESOME Shop - Customizer - Concrete Wall Material

### Building Straight Block

|                              |
|------------------------------|
| `rail-straight-block_pillar` |
| `rail-straight`              |
| `rail-straight`              |
| `rail-straight`              |
| `rail-straight-block_pillar` |

- Connect `rail-straight-block_pillar` with cable.
- Build railway between `rail-straight-block_pillar`.
- Build pillars.

### Building Curve Block

|                     |                     |                     |
|---------------------|---------------------|---------------------|
| `rail-entry_pillar` | `rail-curve-branch` | `rail-curve-back`   |
|                     | `rail-curve-corner` | `rail-curve-branch` |
|                     |                     | `rail-entry_pillar` |

- Connect `rail-entry_pillar` and `rail-curve-back` with cable.
- Build railway from `rail-curve-branch` to start of `rail-entry_pillar`.
- Build railway outer curve between `rail-curve-branch` blueprints `rail-curve-branch`.
- Build railway inner curve between `rail-curve-branch` blueprints.
- Remove straight railway on `rail-curve-branch`.
- Add block signals.
- Build pillars.

> [!IMPORTANT]
> Inside curve is too short for a 1+4 train. If curve block is built between straight blocks then either
> `rail-entry-pillar` can be used.

### Building T-Junction Block

|                     |                     |                     |                     |                     |
|---------------------|---------------------|---------------------|---------------------|---------------------|
| `rail-entry_pillar` | `rail-junc-branch`  | `rail-junc-back`    | `rail-junc-branch`  | `rail-entry_pillar` |
|                     | `rail-curve-corner` | `rail-junc-branch`  | `rail-curve-corner` |                     |
|                     |                     | `rail-entry_pillar` |

- Connect `rail-entry_pillar` and `rail-junc-back` with cable.
- Build railway from `rail-junc-branch` to start of `rail-entry_pillar`.
- Build outside curve from center `rail-junc-branch` to side `rail-junc-branch`. They cross each other.
- Build inside curve from center `rail-junc-branch` to side `rail-entry_pillar`.
- Add path and block signals.
- Build pillars.

> [!IMPORTANT]
> If junction is immediate followed by another junction then the part between them is too short for a 1+4 train and path
> signals need to be used.

### Building Train Stations

| single sided                    | | double sided                   |
|---------------------------------|-|--------------------------------|
| `rail-entry_pillar`             | | `rail-entry_pillar`            |
| `rail-straight-one_wall`        | | `rail-straight-no_wall`        |
| `rail-curve-branch`             | | `rail-junc-branch`             |
| `rail-straight-one_wall`        | | `rail-straight-no_wall`        |
| `rail-straight-one_wall_pillar` | | `rail-straight-no_wall_pillar` |
| `rail-straight-one_wall`        | | `rail-straight-no_wall`        |
| `rail-curve-branch`             | | `rail-junc-branch`             |
| `rail-straight-one_wall`        | | `rail-straight-no_wall`        |
| `rail-entry_pillar`             | | `rail-entry_pillar`            |

- Connect `rail-entry_pillar`and `rail-straight-one_wall_pillar`/`rail-straight-no_wall_pillar` with cable.
- Build station railway.
- Add path and block signals.
- Build pillars.

### Building Slopes

| up                           | | down                         |
|------------------------------|-|------------------------------|
| `rail-straight-block_pillar` | | `rail-straight-block_pillar` |
| `rail-slope-1st`             | | `rail-slope-3rd`             |
| `rail-slope-2nd`             | | `rail-slope-2nd`             |
| `rail-slope-3rd`             | | `rail-slope-1st`             |
| `rail-straight-block_pillar` | | `rail-straight-block_pillar` |

The `rail-slope-adjuster_large` can be used to snap horizontal railway system blueprints on the underside on the correct
height by extending 4 m foundations.

#### Build Slope Up
- Place `rail-straight-block_pillar`, `rail-slope-1st` and `rail-slope-2nd`.
- Build 3 double ramp 4 m upwards.
- Place `rail-slope-adjuster` snapping to double ramp.
- Place another `rail-slope-adjuster` on top of previous.
- Remove first `rail-slope-adjuster`.
- Place `rail-straight-block_pillar` snapping to underside of `rail-slope-adjuster`.
- Remove second `rail-slope-adjuster` and extra double ramp.
- Place `rail-slope-3rd` from snapping to `rail-straight-block_pillar`.
- Connect railway. The railway on `rail-slope-1st` and `rail-slope-3rd` are to minimise slope curvature (only first and last twelve meter affected). They could in theory be removed after slope curves are built.
- Build pillars.

#### Build Slope Down
- Place `rail-straight-block_pillar` and `rail-slope-3rd`.
- Build 6 double ramp 4 m downwards. Build an L of 2 m foundations from double ramp and to the side.
- Place `rail-slope-adjuster` snapping to the 2 m foundations.
- Place another `rail-slope-adjuster` on top of previous.
- Remove first `rail-slope-adjuster` and extra foundations on the side.
- Place `rail-straight-block_pillar` snapping to underside of `rail-slope-adjuster`.
- Remove second `rail-slope-adjuster` and extra double ramps.
- Place `rail-slope-1st` and `rail-slope-2nd` snapping to `rail-straight-block_pillar`.
- Connect railway. The railway on `rail-slope-1st` and `rail-slope-3rd` are to minimise slope curvature (only first and last twelve meter affected). They could in theory be removed after slope curves are built.
- Build pillars.

## Power

### Biomass
- `pow-mk3-biofuel`
- `pow-mk3-biomass_burner`

### Coal
- `pow-mk3-mk1-coal_generator-L`
- `pow-mk3-mk1-coal_generator-R`
- `pow-mk3-compacted_coal`
- `pow-mk5-compacted_coal`

### Fuel
- `pow-fuel_generator`
- `pow-fuel_generator_junction`
- `pow-mk1-residual_fuel`
- `pow-mk2-residual_fuel`
- `pow-mk3-mk1-fuel_L`
- `pow-mk3-mk2-fuel_L`
- `pow-mk3-mk1-fuel_R`
- `pow-mk3-mk2-fuel_R`
- `pow-mk3-mk2-turbofuel_L`
- `pow-mk3-mk2-turbofuel_R`
- `pow-mk5-mk2-fuel_L`
- `pow-mk5-mk2-fuel_R`
- `pow-mk5-mk2-turbofuel_L`
- `pow-mk5-mk2-turbofuel_R`

### Storage
- `pow-power_storage`
