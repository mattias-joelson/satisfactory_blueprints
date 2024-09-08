# satisfactory_blueprints
Blueprints for Satisfactory game.

## Production Factories

Ground level of factory consist of the production floor and the basement. Factory modules are placed on the production
floor and the interconnection between them are handled on the basement floor.

### Parts
- prod-parts-module_floor
- prod-parts-wall
- prod-parts-wall_doors
- prod-parts-empty_module_floor
- prod-parts-empty_module
- prod-mk3-refinery_L_R
- prod-mk3-refinery_R_L
- prod-mk3-mk1-refinery_L_R
- prod-mk3-mk1-refinery_R_L
- prod-mk3-manufacturer_3
- prod-mk3-manufacturer
- prod-mk5-mk2-refinery_L_R
- prod-mk5-mk2-refinery_R_L
- prod-mk5-mk1-blender
- prod-mk5-mk2-blender

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
- AWESOME Shop - Foundations - Inverted Ramp Set (inverted ramp)
- AWESOME Shop - Architecture - Modern Railing (modern railing)
- AWESOME Shop - Architecture - Modern Catwalks (catwalks)
- AWESOME Shop - Customizer - Concrete Foundation Material
- AWESOME Shop - Customizer - Concrete Wall Material

### Module Foundation - two layers of 1 m foundation, 8 m vertical in between
- prod-mod_found-empty - 4x4 1 m foundation
- prod-mod_found-1_1 - 4x4 1 m foundation, 1 input hole, 1 output hole
- prod-mod_found-1_2_wire_cable - 4x4 1 m foundation, 1 input hole, 2 output hole
- prod-mod_found-2_1 - 4x4 1 m foundation, 2 input hole, 1 output hole
- prod-mod_found-2_1_intermediate - 4x4 1 m foundation, 1 input hole (intermediate), 1 input hole, 1 output hole
- prod-mod_found-3_1 - 4x4 1 m foundation, 3 input hole, 1 output hole
- prod-mod_found-3_1_intermediate - 4x4 1 m foundation, 1 input hole (intermediate), 2 input hole, 1 output hole
- prod-mod_found-4_1 - 4x4 1 m foundation, 4 input hole, 1 output hole
- prod-mod_found-4_1_intermediate - 4x4 1 m foundation, 1 input hole (intermediate), 3 input hole, 1 output hole
- prod-mod_found-2_1_1_0 - 4x4 1 m foundation, 2 input hole, 1 input pipe hole, 0 output hole, 1 output pipe hole
- prod-mod_found-2_1_1_1 - 4x4 1 m foundation, 2 input hole, 1 input pipe hole, 1 output hole, 1 output pipe hole
- prod-mod_found-2_2_1_0 - 4x4 1 m foundation, 2 input hole, 2 input pipe hole, 1 output hole, 0 output pipe hole
- prod-mod_found-2_2_1_1 - 4x4 1 m foundation, 2 input hole, 2 input pipe hole, 1 output hole, 1 output pipe hole
- prod-mod_found-12 - 4x4 1 m foundation, 12 input hole (for storage)
- prod-mod_found-18 - 4x4 1 m foundation, 18 input hole (for storage)

### Module
- prod-module-stairs - catwalk stairs between modules
- prod-module-stairs_top - catwalk stairs between modules, top floor
- prod-module-stairs_outside - catwalk stairs between modules, outermost
- prod-module-stairs_outside_top - catwalk stairs between modules, outermost, top floor
- prod-module-storage - 12 storage container
- prod-module-storage_18 - 18 storage container
- prod-module-storage_18_nosign - 18 storage container (no signs)

## Production mk2

### Smelter mk2
- prod-mk2-iron_ingot
- prod-mk2-copper_ingot
- prod-mk2-steel_ingot

### Constructor mk2
- prod-mk2-iron_plate
- prod-mk2-iron_rod
- prod-mk2-cable
- prod-mk2-cable_wire_bottom
- prod-mk2-copper_sheet
- prod-mk2-concrete
- prod-mk2-steel_beam
- prod-mk2-steel_pipe

### Assembler mk2
- prod-mk2-reinforced_plate
- prod-mk2-rotor
- prod-mk2-modular_frame
- prod-mk2-encased_industrial_beam

## Production mk3

### Smelter mk3
- prod-mk3-iron_ingot
- prod-mk3-copper_ingot
- prod-mk3-caterium_ingot

### Foundry mk3
- prod-mk3-steel_ingot
- prod-mk3-aluminum_ingot
- prod-mk3-aluminum_ingot_top

### Constructor mk3
- prod-mk3-iron_plate
- prod-mk3-iron_rod
- prod-mk3-cable
- prod-mk3-cable_wire_bottom
- prod-mk3-copper_sheet
- prod-mk3-concrete
- prod-mk3-steel_beam
- prod-mk3-steel_pipe
- prod-mk3-empty_canister
- prod-mk3-quartz_crystal
- prod-mk3-silica

### Assembler mk3
- prod-mk3-reinforced_plate
- prod-mk3-rotor
- prod-mk3-modular_frame
- prod-mk3-encased_industrial_beam
- prod-mk3-stator
- prod-mk3-motor
- prod-mk3-circuit_board
- prod-mk3-alclad_aluminum_sheet
- prod-mk3-ai_limiter
- prod-mk3-compacted_coal
- prod-mk3-black_powder
- prod-mk3-nobelisk
- prod-mk3-rifle_ammo
- prod-mk3-gas_filter
- prod-mk3-smart_plating.sbp
- prod-mk3-versatile_framework.sbp
- prod-mk3-automated_wiring

### Manufacturer mk3
- prod-mk3-heavy_modular_frame
- prod-mk3-computer
- prod-mk3-crystal_oscillator
- prod-mk3-high-speed_connector
- prod-mk3-supercomputer.sbp
- prod-mk3-modular_engine
- prod-mk3-adaptive_control_unit

### Refinery mk3
- prod-mk3-plastic_L
- prod-mk3-plastic_R
- prod-mk3-rubber_L
- prod-mk3-rubber_R
- prod-mk3-fuel_L
- prod-mk3-fuel_R
- prod-mk3-residual_plastic_L_R
- prod-mk3-residual_plastic_R_L
- prod-mk3-residual_rubber_L_R
- prod-mk3-residual_rubber_R_L
- prod-mk3-residual_fuel
- prod-mk3-polyester_fabric_L_R
- prod-mk3-polyester_fabric_R_L
- prod-mk3-turbofuel_L
- prod-mk3-turbofuel_R
- prod-mk3-smokeless_powder_L_R
- prod-mk3-smokeless_powder_R_L
- prod-mk3-alumina_solution_L_R
- prod-mk3-alumina_solution_R_L
- prod-mk3-aluminum_scrap_L_R
- prod-mk3-aluminum_scrap_R_L

## Production mk5

### Smelter mk5
- prod-mk5-iron_ingot
- prod-mk5-copper_ingot
- prod-mk5-caterium_ingot

### Foundry mk5
- prod-mk5-steel_ingot
- prod-mk5-aluminum_ingot
- prod-mk5-aluminum_ingot_top

### Constructor mk5
- prod-mk5-iron_plate
- prod-mk5-iron_rod
- prod-mk5-cable
- prod-mk5-copper_sheet
- prod-mk5-concrete
- prod-mk5-steel_beam
- prod-mk5-steel_pipe
- prod-mk5-aluminum_casing
- prod-mk5-quartz_crystal
- prod-mk5-silica
- prod-mk5-quickwire

### Assembler mk5
- prod-mk5-reinforced_plate
- prod-mk5-rotor
- prod-mk5-encased_industrial_beam
- prod-mk5-stator
- prod-mk5-motor
- prod-mk5-circuit_board
- prod-mk5-alclad_aluminum_sheet
- prod-mk5-heat_sink
- prod-mk5-ai_limiter
- prod-mk5-electromagnetic_control
- prod-mk5-magnetic_field_generato

### Manufacturer mk5
- prod-mk5-heavy_modular_frame
- prod-mk5-modular_frame
- prod-mk5-computer
- prod-mk5-crystal_oscillator
- prod-mk5-high-speed_connector
- prod-mk3-supercomputer.sbp
- prod-mk5-radio_control_unit
- prod-mk5-turbo_motor

### Refinery mk5
- prod-mk5-mk2-plastic_L.sbp
- prod-mk5-mk2-plastic_R.sbp
- prod-mk5-mk2-rubber_L.sbp
- prod-mk5-mk2-rubber_R.sbp
- prod-mk5-alumina_solution_L_R
- prod-mk5-alumina_solution_R_L
- prod-mk5-aluminum_scrap_L_R
- prod-mk5-aluminum_scrap_R_L

### Blender mk5 mk1
- prod-mk5-mk2-fused modular frame (TODO: byt namn)
- prod-mk5-mk1-encased_uranium_cel
- prod-mk5-mk2-cooling_system
- prod-mk5-mk1-turbo_rifle_ammo

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
- logi-balancer-2_2_mk5_high
- logi-balancer-2_3_mk5
- logi-balancer-2_4_mk5
- logi-balancer-3_3_mk5
- logi-balancer-4_4_mk5

## Fluid

### Control, pumps
- fluid-ctrl-1_horizontal_pump_mk1
- fluid-ctrl-2_horizontal_pump_mk1
- fluid-ctrl-3_horizontal_pump_mk1
- fluid-ctrl-1_vertical_pump_mk1
- fluid-ctrl-1_vertical_pump_mk2
- fluid-ctrl-2_vertical_pump_mk1
- fluid-ctrl-2_vertical_pump_mk2
- fluid-ctrl-3_vertical_pump_mk1

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

| blueprint                       | walled foundation  | railway            | block signals      | electric connection | pillar top with sockets | used for                                                                                  |
|---------------------------------|--------------------|--------------------|--------------------|---------------------|-------------------------|-------------------------------------------------------------------------------------------|
| `rail-straight`                 | :white_check_mark: |                    |                    |                     |                         | Straight blocks.                                                                          |
| `rail-straight-block_pillar`    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark:  | :white_check_mark:      | Straight blocks, every fourth blueprint.                                                  |
| `rail-straight-no_wall`         | :white_check_mark: |                    |                    |                     |                         | Double sided stations.                                                                    |
| `rail-straight-no_wall_pillar`  | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Double sided stations.                                                                    |
| `rail-straight-one_wall`        | :white_check_mark: |                    |                    |                     |                         | Single sided stations.                                                                    |
| `rail-straight-one_wall_pillar` | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Single sided stations.                                                                    |
|                                 |                    |                    |                    |                     |                         |                                                                                           |
| `rail-entry_pillar`             | :white_check_mark: |                    |                    | :white_check_mark:  | :white_check_mark:      | Pillar support where signaling is done by hand (instead of `rail-straight-block_pillar`). |
| `rail-curve-branch`             | :white_check_mark: | :white_check_mark: |                    |                     |                         | Curve block, single sided stations.                                                       |
| `rail-curve-back`               | :white_check_mark: |                    |                    | :white_check_mark:  |                         | Curve block.                                                                              |
| `rail-curve-corner`             | :white_check_mark: |                    |                    |                     |                         | Curve and junction block.                                                                 |
| `rail-junc-branch`              | :white_check_mark: | :white_check_mark: |                    |                     |                         | Junction block, double sided stations.                                                    |
| `rail-junc-back`                | :white_check_mark: |                    |                    | :white_check_mark:  |                         | Junction block.                                                                           |
|                                 |                    |                    |                    |                     |                         |                                                                                           |
| `rail-slope-1st`                | :white_check_mark: | :white_check_mark: |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-2nd`                | :white_check_mark: |                    |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-3rd`                | :white_check_mark: | :white_check_mark: |                    |                     |                         | Slope block.                                                                              |
| `rail-slope-adjuster`           |                    |                    |                    |                     |                         | For placing parts of slope blocks.                                                        |
| `rail-slope-adjuster_large`     |                    |                    |                    |                     |                         | For placing parts of slope blocks.                                                        |

Uses parts from
- HUB Upgrade 2 (power line)
- HUB Upgrade 3 (power pole)
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

### Straight Railways
- rail-straight-foundation - 4x4 2 m foundations
- rail-straight-block_signal - 4x4 2 m foundations, railways, block signals
- rail-straight-pillar - pillar to go underneath supported squares

### Curve and T-Junction
- rail-junction-entrance - 4x4 2 m foundations, railways
- rail-junction-back - 4x4 2 m foundations, for connecting branching direction
- rail-junction-branch - 4x4 2 m foundations, for branching direction
- rail-junction-corner - inner corner extension 2 m

## Power

### Parts
- pow-parts-biomass_burner_floor

### Biomass
- pow-biomass-biomass_constructor
- pow-biomass-biomass_const_nosign
- pow-biomass-biomass_burner

### Coal
- pow-coal-generator_mk2_L
- pow-coal-generator_mk2_R
- pow-coal-generator_mk3_L
- pow-coal-generator_mk3_R
- pow-coal-petroleum_coke_L
- pow-coal-petroleum_coke_R

### Fuel
- pow-fuel-generator
- pow-fuel-residual_fuel

### Storage
- pow-storage-power_storage
