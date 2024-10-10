# satisfactory_blueprints
Blueprints for Satisfactory game.

## Production Factories

Ground level of factory consist of the production floor and the basement. Factory modules are placed on the production
floor and the interconnection between them are handled on the basement floor.

### Parts

### Production Floor Grid

| blueprint                          | usage                                                                                                              |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| `prod-grid-corner`                 | Corners of production floor grid.                                                                                  |
| `prod-grid-corner_outlet`          | Corner of production floor grid with power outlets. Connects electricity on basement floor and underneath factory. |
| `prod-grid-connect`                | Connects production floor grid corners.                                                                            |
| `prod-grid-connect_stairs`         | Connects production floor grid corners. Stairs between production floor and basement.                              |
| `prod-grid-connect_stairwell`      | Connects production floor grid corners. Stairs between production floor, basement and underside.                   |
|                                    |                                                                                                                    |
| `prod-floor-corner_outside`        | Decoration outside of factory floor corners.                                                                       |
| `prod-floor-corner_pillar_outside` | Decoration outside of factory floor corners (for pillars).                                                         |
| `prod-floor-connect_outside`       | Decoration outside of factory floor connections.                                                                   |

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

### Production Floor Support
- `prod-found-pillar_base`
- `prod-found-pillar_base_ext`
- `prod-found-pillar_support`

Uses parts from
- Tier 1 - Base Building (foundation, ramp, wall)
- AWESOME Shop - Foundations - Inverted Ramp Set (inverted ramp)
- AWESOME Shop - Foundations - Corner Ramp Pack (up corner)
- AWESOME Shop - Customizer - Concrete Foundation Material

### Module Production Floor

Two layers of 4m foundation, 8++ m vertical in between. Wall outlet under the top layer in the corners, connect with cables.

| parts blueprint               | notes |
|-------------------------------|-------|
| `prod-parts-production_floor` |       |

| blueprint              | input holes | intermediate input hole | input pipe holes |    output hole     |  output pipe hole  | used for                                                                                               |
|------------------------|:-----------:|:-----------------------:|:----------------:|:------------------:|:------------------:|--------------------------------------------------------------------------------------------------------|
| `prod-floor-empty`     |             |                         |                  |                    |                    | no wiring, used for non-electric modules (train stations, mall)                                        |
| `prod-floor-1-1`       |      1      |                         |                  | :white_check_mark: |                    | for one-ingredient parts (smelter, constructor)                                                        |
| `prod-floor-1-1-cable` |      1      |                         |                  | :white_check_mark: |                    | for cable                                                                                              |
| `prod-floor-2-1`       |      2      |                         |                  | :white_check_mark: |                    | for two-ingredient parts (foundry, assembler)                                                          |
| `prod-floor-2i-1`      |      2      |   :white_check_mark:    |                  | :white_check_mark: |                    | for two-ingredient parts where one intermediate is manufactured locally (example: rotors using screws) |
| `prod-floor-3-1`       |      3      |                         |                  | :white_check_mark: |                    | for three-ingredient parts (manufacturer)                                                              |
| `prod-floor-3i-1`      |      3      |   :white_check_mark:    |                  | :white_check_mark: |                    | for three-ingredient parts where one intermediate is manufactured locally (manufacturer)               |
| `prod-floor-4-1`       |      4      |                         |                  | :white_check_mark: |                    | for four-ingredient parts (manufacturer)                                                               |
| `prod-floor-4i-1`      |      4      |   :white_check_mark:    |                  | :white_check_mark: |                    | for four-ingredient parts where one intermediate is manufactured locally (manufacturer)                |
| `prod-floor-1-2-0-1`   |      1      |                         |        2         |                    | :white_check_mark: | for blender                                                                                            |
| `prod-floor-2-1-1-0`   |      2      |                         |        1         | :white_check_mark: |                    | for blender                                                                                            |
| `prod-floor-2-1-1-1`   |      2      |                         |        1         | :white_check_mark: | :white_check_mark: | for blender                                                                                            |
| `prod-floor-2-2-1-0`   |      2      |                         |        2         | :white_check_mark: |                    | for blender                                                                                            |
| `prod-floor-2-2-1-1`   |      2      |                         |        2         | :white_check_mark: | :white_check_mark: | for blender                                                                                            |
| `prod-floor-1-0--1`    |      1      |                         |        0         | :white_check_mark: |                    | for particle accelerator                                                                               |
| `prod-floor-1-1--1`    |      1      |                         |        1         | :white_check_mark: |                    | for particle accelerator                                                                               |
| `prod-floor-2-0--1`    |      2      |                         |        0         | :white_check_mark: |                    | for particle accelerator                                                                               |
| `prod-floor-2-1--1`    |      2      |                         |        1         | :white_check_mark: |                    | for particle accelerator                                                                               |
| `prod-floor-0--0-1`    |      0      |                         |                  |                    | :white_check_mark: | for converter                                                                                          |
| `prod-floor-1--0-1`    |      1      |                         |                  |                    | :white_check_mark: | for converter                                                                                          |
| `prod-floor-1--1-0`    |      1      |                         |                  | :white_check_mark: |                    | for converter                                                                                          |
| `prod-floor-2--1-0`    |      2      |                         |                  | :white_check_mark: |                    | for converter                                                                                          |
| `prod-floor-2--1-1`    |      2      |                         |                  | :white_check_mark: | :white_check_mark: | for converter                                                                                          |
| `prod-floor-storage`   |     18      |                         |                  |                    |                    | for `prod-module-storage`                                                                              |

Uses parts from
- Tier 0 - HUB Upgrade 2 (power line)
- Tier 1 - Base Building (foundation, ramp, wall)
- AWESOME Shop - Management - Conveyor Lift Floor Hole (conveyor lift floor hole)
- AWESOME Shop - Management - Wall Power Outlets Mk.1 (wall outlet)
- AWESOME Shop - Management - Pipeline Floor Hole (pipeline floor hole)
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
- `prod-mk3-copper_sheet`
- `prod-mk3-steel_beam`
- `prod-mk3-steel_pipe`
- `prod-mk3-wire`
- `prod-mk3-cable` (intermediate wire)
- `prod-mk3-reanimated_SAM`
- `prod-mk3-concrete`

### Assembler mk3
- `prod-mk3-smart_plating`
- `prod-mk3-versatile_framework`
- `prod-mk3-automated_wiring`
- `prod-mk3-reinforced_iron_plate` (intermediate screws)
- `prod-mk3-modular_frame`
- `prod-mk3-encased_industrial_beam`
- `prod-mk3-circuit_board`
- `prod-mk3-rotor` (intermediate screws)
- `prod-mk3-stator` (intermediate wire)
- `prod-mk3-motor`
- `prod-mk3-black_powder`
- `prod-mk3-nobelisk`
- `prod-mk3-rifle_ammo`

### Manufacturer mk3
- `prod-mk3-modular_engine`
- `prod-mk3-adaptive_control_unit`
- `prod-mk3-heavy_modular_frame`
- `prod-mk3-SAM_fluctuator`
- `prod-mk3-computer`

### Refinery mk3
- `prod-mk3-mk1-plastic_L`
- `prod-mk3-mk2-plastic_L`
- `prod-mk3-mk1-plastic_R`
- `prod-mk3-mk2-plastic_R`
- `prod-mk3-mk1-rubber_L`
- `prod-mk3-mk2-rubber_L`
- `prod-mk3-mk1-rubber_R`
- `prod-mk3-mk2-rubber_R`
- `prod-mk3-mk1-alumina_solution_LR`
- `prod-mk3-mk1-aluminum_scrap_LR`
- `prod-mk3-mk2-smokeless_powder_LR`
- `prod-mk3-mk2-smokeless_powder_RL`

## Production mk5

| template blueprint                 | module production floor | notes                  |
|------------------------------------|-------------------------|------------------------|
| `prod-mk5-smelter`                 | `prod-floor-1-1`        | 16 smelters            |
| `prod-mk5-foundry`                 | `prod-floor-2-1`        | 6 foundry              |
| `prod-mk5-constructor`             | `prod-floor-1-1`        | 12 constructors        |
| `prod-mk5-assembler`               | `prod-floor-2-1`        | 6 assemblers           |
| `prod-mk5-manufacturer`            | `prod-floor-4-1`        | 2 manufacturer         |
| `prod-mk5-manufacturer_3`          | `prod-floor-3-1`        | 2 manufacturer         |
| `prod-mk5-mk2-refinery_LR`         | `prod-floor-empty`      | 3 refinery             |
| `prod-mk5-mk2-refinery_RL`         | `prod-floor-empty`      | 3 refinery             |
| `prod-mk5-mk2-packager_LR`         | `prod-floor-empty`      | 4 packager             |
| `prod-mk5-mk2-packager_RL`         | `prod-floor-empty`      | 4 packager             |
| `prod-mk5-mk2-blender`             | `prod-floor-2-2-1-1`    | 1 blender              |
| `prod-mk5-mk2-particle_accelerato` | `prod-floor-2-1-1`      | 1 particle accelerator |
| `prod-mk5-mk2-converter`           | `prod-floor-2--1-1`     | 2 converter            |

> [!IMPORTANT]
> `prod-mk5-mk2-particle_accelerato` is actually 4 foundations wide and 5 long. This mean that it will occupy the
> connect part one the cable connection side.

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
- Tier 7 - Control System Development (blender)
- Tier 8 - Particle Enrichment (particle accelerator)
- Tier 9 - Matter Conversion (converter)
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
- `prod-mk5-steel_ingot`
- `prod-mk5-aluminum_ingot`
- `prod-mk5-aluminum_ingot_top`

### Constructor mk5
- `prod-mk5-iron_plate`
- `prod-mk5-iron_rod`
- `prod-mk5-copper_sheet`
- `prod-mk5-steel_beam`
- `prod-mk5-steel_pipe`
- `prod-mk5-aluminum_casing`
- `prod-mk5-ficsite_trigon`
- `prod-mk5-wire`
- `prod-mk5-cable` (intermediate wire)
- `prod-mk5-quickwire`
- `prod-mk5-reanimated_SAM`
- `prod-mk5-concrete`
- `prod-mk5-quartz_crystal`
- `prod-mk5-silica`
- `prod-mk5-empty_canister`

### Assembler mk5
- `prod-mk5-smart_plating`
- `prod-mk5-versatile_framework`
- `prod-mk5-automated_wiring`
- `prod-mk5-assembly_directory_syst`
- `prod-mk5-reinforced_iron_plate`
- `prod-mk5-modular_frame`
- `prod-mk5-encased_industrial_beam`
- `prod-mk5-alclad_aluminum_sheet`
- `prod-mk5-circuit_board`
- `prod-mk5-AI_limiter`
- `prod-mk5-rotor`
- `prod-mk5-stator`
- `prod-mk5-motor`
- `prod-mk5-heat_sink`
- `prod-mk5-electromagnetic_control`
- `prod-mk5-black_powder`
- `prod-mk5-nobelisk`
- `prod-mk5-rifle_ammo`

### Manufacturer mk5
- `prod-mk5-modular_engine`
- `prod-mk5-adaptive_control_unit`
- `prod-mk5-thermal_propulsion_rock`
- `prod-mk5-ballistic_warp_drive`
- `prod-mk5-heavy_modular_frame`
- `prod-mk5-high-speed_connector`
- `prod-mk5-singularity_cell`
- `prod-mk5-SAM_fluctuator`
- `prod-mk5-turbo_motor`
- `prod-mk5-computer`
- `prod-mk5-supercomputer`
- `prod-mk5-crystal_oscillator`
- `prod-mk5-radio_control_unit`
- `prod-mk5-gas_filter`
- `prod-mk5-iodine-infused_filter`

### Refinery mk5
- `prod-mk5-mk2-plastic_L`
- `prod-mk5-mk2-plastic_R`
- `prod-mk5-mk2-residual_plastic_LR`
- `prod-mk5-mk2-residual_plastic_RL`
- `prod-mk5-mk2-rubber_L`
- `prod-mk5-mk2-rubber_R`
- `prod-mk5-mk1-alumina_solution_LR`
- `prod-mk5-mk1-alumina_solution_RL`
- `prod-mk5-mk1-aluminum_scrap_LR`
- `prod-mk5-mk1-aluminum_scrap_RL`
- `prod-mk5-mk2-sulfuric_acid_L`
- `prod-mk5-mk2-sulfuric_acid_R`
- `prod-mk5-mk2-polyester_fabric_LR`
- `prod-mk5-mk2-polyester_fabric_RL`
- `prod-mk5-mk2-smokeless_powder_LR`
- `prod-mk5-mk2-smokeless_powder_RL`

### Packager mk5
- `prod-mk5-mk2-packaged_water_LR`
- `prod-mk5-mk2-packaged_water_RL`

### Blender mk5
- `prod-mk5-mk2-bichemical_sculptor`
- `prod-mk5-mk2-nitric_acid`
- `prod-mk5-mk2-cooling_system`
- `prod-mk5-mk2-fused_modular_frame`

### Particle Accelerator mk5
- `prod-mk5-mk2-dark_matter_crystal`
- `prod-mk5-diamonds`

### Converter mk5
- `prod-mk5-time_crystal`
- `prod-mk2-excited_photonic_matter`
- `prod-mk5-mk2-dark_matter_residue`
- `prod-mk5-ficsite_ingot_AI`

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
- `logi-balancer-2_3_mk5`
- logi-balancer-2_4_mk5
- `logi-balancer-3_3_mk5`
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
- `fluid-load-mk2`
- fluid-unload-mk1
- `fluid-unload-mk2`


### Buffer
- fluid-buffer-mk1 - 4 fluid buffer, pipes mk1 (300)
- fluid-buffer-mk2 - 4 fluid buffer, pipes mk2 (600)

## Railway System

All railway blueprints are 3 x 3 foundations using concrete only. Blueprints with electric connection should be
connected with cable so that the pillar sockets provide electricity.

| blueprint                         | walled foundation  |      railway       |   block signals    | electric connection | pillar top with sockets | used for                                                                                  |
|-----------------------------------|:------------------:|:------------------:|:------------------:|:-------------------:|:-----------------------:|-------------------------------------------------------------------------------------------|
| `rail-straight`                   | :white_check_mark: |                    |                    |                     |                         | Straight blocks.                                                                          |
| `rail-straight-block_pillar`      | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:  |   :white_check_mark:    | Straight blocks, every fourth blueprint.                                                  |
| `rail-straight-block_temp_pillar` | :white_check_mark: | :white_check_mark: |                    | :white_check_mark:  |   :white_check_mark:    | Straight blocks, every fourth blueprint. NOTE! Placeholder for block signals.             |
| `rail-straight-no_wall`           | :white_check_mark: |                    |                    |                     |                         | Double sided stations.                                                                    |
| `rail-straight-no_wall_pillar`    | :white_check_mark: |                    |                    | :white_check_mark:  |   :white_check_mark:    | Double sided stations.                                                                    |
| `rail-straight-one_wall`          | :white_check_mark: |                    |                    |                     |                         | Single sided stations.                                                                    |
| `rail-straight-one_wall_pillar`   | :white_check_mark: |                    |                    | :white_check_mark:  |   :white_check_mark:    | Single sided stations.                                                                    |
|                                   |                    |                    |                    |                     |                         |                                                                                           |
| `rail-entry_pillar`               | :white_check_mark: |                    |                    | :white_check_mark:  |   :white_check_mark:    | Pillar support where signaling is done by hand (instead of `rail-straight-block_pillar`). |
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

| blueprints single sided         | amount |
|---------------------------------|-------:|
| `prod-floor-empty`              |      4 |
|                                 |        |
| `prod-grid-corner`              |      9 |
| `prod-grid-corner_outlet`       |      6 |
| `prod-grid-connect`             |     14 |
| `prod-grid-connect_stairs`      |      8 |
|                                 |        |
| `rail-straight-one_wall`        |      4 |
| `rail-curve-branch`             |      2 |
| `rail-straight-one_wall_pillar` |      1 |

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
- `pow-mk5-mk2-fuel_L`
- `pow-mk5-mk2-fuel_R`
- `pow-mk2-residual_fuel`
- `pow-mk3-mk2-turbofuel_L`
- `pow-mk3-mk2-turbofuel_R`
- `pow-mk5-mk2-turbofuel_L`
- `pow-mk5-mk2-turbofuel_R`
- `pow-fuel_generator`
- `pow-fuel_generator_junction`

### Nuclear Power Plant
- `pow-mk5-encased_plutonium_cell`
- `pow-mk5-uranium_fuel_rod`
- `pow-mk5-plutonium_fuel_rod`
- `pow-mk5-mk2-encased_uranium_cell`
- `pow-mk5-mk2-non-fissile_uranium`
- `pow-mk5-plutonium_pellet`
- `pow-npp_floor-corner_outlet`
- `pow-npp_floor-corner`
- `pow-npp_floor-connect`
- `pow-npp_floor-connect_plants`
- `pow-npp_floor-connect_plants_L` (for single row of plants)
- `pow-npp_floor-placement`
- `pow-npp_floor`
- `pow-npp_floor_empty` (for floor with no nuclear plant)

The nuclear power plants does not fit well on 4x4 foundation so blueprints mk2 where needed. First build the grid and
place `pow-npp_floor-placement` between the lines to simplify water extractor placement. Note that arrow for
`pow-npp_floor-connect_plants` points towards waste direction.

|                               |                                |                          |                                |                               |
|-------------------------------|--------------------------------|--------------------------|--------------------------------|-------------------------------|
| `pow-npp_floor-corner_outlet` | `pow-npp_floor-connect`        | `pow-npp_floor-corner`   | `pow-npp_floor-connect`        | `pow-npp_floor-corner_outlet` |
| `pow-npp_floor-connect`       | `pow-npp_floor-placement`      | `pow-npp_floor-connect`  | `pow-npp_floor-placement`      | `pow-npp_floor-connect`       |
| `pow-npp_floor-corner`        | `pow-npp_floor-connect_plants` | `pow-npp_floor-corner`   | `pow-npp_floor-connect_plants` | `pow-npp_floor-corner`        |
| `pow-npp_floor-connect`       | `pow-npp_floor-placement`      | `pow-npp_floor-connect`  | `pow-npp_floor-placement`      | `pow-npp_floor-connect`       |
| `pow-npp_floor-corner_outlet` | `pow-npp_floor-connect`        | `pow-npp_floor-corner`   | `pow-npp_floor-connect`        | `pow-npp_floor-corner_outlet` |

Align the water extractors on the pipe junctions. To get the correct distance zoop a line of foundations between the
`pow-npp_floor-corner` to move up against. For optimal alignment nudge that line two small steps towards yourself. Then remove
the alignment foundations and place the neighbouring water extractors. They will snap to the ones already placed.

Dismantle the `pow-npp_floor-placement` and place the actual `pow-npp_floor` for the power plants. Entrance to the
basement is to the right when looking on the plant inputs.

|                               |                                |                         |                                |                               |
|-------------------------------|--------------------------------|-------------------------|--------------------------------|-------------------------------|
| `pow-npp_floor-corner_outlet` | `pow-npp_floor-connect`        | `pow-npp_floor-corner`  | `pow-npp_floor-connect`        | `pow-npp_floor-corner_outlet` |
| `pow-npp_floor-connect`       | `pow-npp_floor`                | `pow-npp_floor-connect` | `pow-npp_floor`                | `pow-npp_floor-connect`       |
| `pow-npp_floor-corner`        | `pow-npp_floor-connect_plants` | `pow-npp_floor-corner`  | `pow-npp_floor-connect_plants` | `pow-npp_floor-corner`        |
| `pow-npp_floor-connect`       | `pow-npp_floor`                | `pow-npp_floor-connect` | `pow-npp_floor`                | `pow-npp_floor-connect`       |
| `pow-npp_floor-corner_outlet` | `pow-npp_floor-connect`        | `pow-npp_floor-corner`  | `pow-npp_floor-connect`        | `pow-npp_floor-corner_outlet` |

Finish off by placing the power plants and connect them. Also hook up the water extractors to the same power pole as the
pump and connect to nearest `pow-npp_floor-corner_outlet`.

### Storage
- `pow-power_storage`

## Sign
- `sign-copper_ingot`
- `sign-steel_ingot`
- `sign-iron_rod`
- `sign-copper_sheet`
- `sign-steel_pipe`
- `sign-rotor`
- `sign-stator`
- `sign-motor`
- `sign-heat_sink`
- `sign-thermal_propulsion_rocket`
- `sign-turbo_motor`
- `sign-cooling_system`
