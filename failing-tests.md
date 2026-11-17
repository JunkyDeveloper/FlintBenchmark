# Failing & flaky Flint tests

Server: vanilla 26.3 dedicated · FlintCLI release (azalea 26.3 fork) · 3 runs, 2026-11-16

| Run | Pass | Fail |
|---|---|---|
| 1 | 1149/1248 | 99 |
| 2 | 1144/1248 | 104 |
| 3 | 1145/1248 | 103 |

## Always failing (93) — failed 3/3

- [ ] `Campfire Shovel From Below Does Nothing` — `tests/decoration/campfires/campfire_shovel_from_below_does_nothing.json`
- [ ] `Crimson Fence Not Fuel` — `tests/connectible/fences/crimson_fence_not_fuel.json`
- [ ] `Crimson Hyphae Not Fuel` — `tests/decoration/hyphae/crimson_hyphae_not_fuel.json`
- [ ] `Oak Fence Furnace Fuel` — `tests/connectible/fences/oak_fence_furnace_fuel.json`
- [ ] `Wolf Collar Dye Baby Wolf` — `tests/entities/wolf/wolf_collar_dye_baby_wolf.json`
- [ ] `Wolf Collar Dye Changes Color` — `tests/entities/wolf/wolf_collar_dye_changes_color.json`
- [ ] `Wolf Collar Dye Creative Keeps Item` — `tests/entities/wolf/wolf_collar_dye_creative_keeps_item.json`
- [ ] `Wolf Collar Dye Same Color Noop` — `tests/entities/wolf/wolf_collar_dye_same_color_noop.json`
- [ ] `Wolf Collar Dye Stack Consumes One` — `tests/entities/wolf/wolf_collar_dye_stack_consumes_one.json`
- [ ] `axe_breaks_after_durability_uses` — `tests/items/axes/axe_breaks_after_durability_uses.json`
- [ ] `bamboo_stacking_on_stalk` — `tests/vegetation/bamboo/bamboo_stacking_on_stalk.json`
- [ ] `beacon_effect_applied_without_level_check` — `tests/decoration/beacons/beacon_effect_applied_without_level_check.json`
- [ ] `beacon_level_four_primary_and_secondary_effects` — `tests/decoration/beacons/beacon_level_four_primary_and_secondary_effects.json`
- [ ] `beacon_level_four_same_effect_amplifier_one` — `tests/decoration/beacons/beacon_level_four_same_effect_amplifier_one.json`
- [ ] `beacon_level_one_speed_effect` — `tests/decoration/beacons/beacon_level_one_speed_effect.json`
- [ ] `bed_placement_head_space` — `tests/decoration/beds/bed_placement_head_space.json`
- [ ] `bed_use_night` — `tests/decoration/beds/bed_use_night.json`
- [ ] `big_dripleaf_place_on_supports` — `tests/vegetation/big_dripleaf/big_dripleaf_place_on_supports.json`
- [ ] `brush_completion_drops_item_on_hit_face` — `tests/items/brush/brush_completion_drops_item_on_hit_face.json`
- [ ] `brush_completion_drops_item_on_top_face` — `tests/items/brush/brush_completion_drops_item_on_top_face.json`
- [ ] `brush_creative_completes_brushing` — `tests/items/brush/brush_creative_completes_brushing.json`
- [ ] `brush_dusting_resets_after_release` — `tests/items/brush/brush_dusting_resets_after_release.json`
- [ ] `brush_looking_at_air_does_nothing` — `tests/items/brush/brush_looking_at_air_does_nothing.json`
- [ ] `brush_on_ordinary_block_does_nothing` — `tests/items/brush/brush_on_ordinary_block_does_nothing.json`
- [ ] `brush_progressive_dusting` — `tests/items/brush/brush_progressive_dusting.json`
- [ ] `bucket_fills_from_full_powder_snow_cauldron` — `tests/items/bucket/bucket_fills_from_full_powder_snow_cauldron.json`
- [ ] `bucket_fills_from_full_water_cauldron` — `tests/items/bucket/bucket_fills_from_full_water_cauldron.json`
- [ ] `bucket_fills_from_lava_cauldron` — `tests/items/bucket/bucket_fills_from_lava_cauldron.json`
- [ ] `cauldron_bucket_fill` — `tests/decoration/cauldrons/cauldron_bucket_fill.json`
- [ ] `cauldron_bucket_under_water` — `tests/decoration/cauldrons/cauldron_bucket_under_water.json`
- [ ] `copper_ore_blast_furnace_smelting` — `tests/world/copper_ore/copper_ore_blast_furnace_smelting.json`
- [ ] `copper_ore_furnace_smelting` — `tests/world/copper_ore/copper_ore_furnace_smelting.json`
- [ ] `copper_slab_waxing` — `tests/building/slabs/copper_slab_waxing.json`
- [ ] `crafting_table_burns_as_furnace_fuel` — `tests/decoration/crafting_table/crafting_table_burns_as_furnace_fuel.json`
- [ ] `crimson_pressure_plate_activation` — `tests/redstone/pressure_plate/crimson_pressure_plate_activation.json`
- [ ] `crimson_stem_not_fuel` — `tests/world/crimson_stem/crimson_stem_not_fuel.json`
- [ ] `crimson_stem_not_smelted_to_charcoal` — `tests/world/crimson_stem/crimson_stem_not_smelted_to_charcoal.json`
- [ ] `deepslate_explosion_drops_cobbled_deepslate` — `tests/decoration/deepslate/deepslate_explosion_drops_cobbled_deepslate.json`
- [ ] `diamond_ore_tnt_explosion_drops_diamond` — `tests/world/diamond_ore/diamond_ore_tnt_explosion_drops_diamond.json`
- [ ] `dirt_path_explosion_drops_dirt` — `tests/world/dirt_path/dirt_path_explosion_drops_dirt.json`
- [ ] `dragon_egg_explosion_destroys_and_drops` — `tests/gravity/dragon_egg/dragon_egg_explosion_destroys_and_drops.json`
- [ ] `emerald_ore_tnt_drops_emerald` — `tests/world/emerald_ore/emerald_ore_tnt_drops_emerald.json`
- [ ] `emerald_ore_tnt_drops_no_experience` — `tests/world/emerald_ore/emerald_ore_tnt_drops_no_experience.json`
- [ ] `end_portal_survives_explosion` — `tests/portal/end_portal/end_portal_survives_explosion.json`
- [ ] `end_rod_explosion_drops_itself` — `tests/decoration/end_rods/end_rod_explosion_drops_itself.json`
- [ ] `ender_chest_survives_tnt_explosion` — `tests/container/ender_chests/ender_chest_survives_tnt_explosion.json`
- [ ] `ender_pearl_second_throw_blocked_by_cooldown` — `tests/items/ender_pearl/ender_pearl_second_throw_blocked_by_cooldown.json`
- [ ] `ender_pearl_throw_again_after_cooldown` — `tests/items/ender_pearl/ender_pearl_throw_again_after_cooldown.json`
- [ ] `ender_pearl_throw_creative_keeps_stack` — `tests/items/ender_pearl/ender_pearl_throw_creative_keeps_stack.json`
- [ ] `ender_pearl_throw_from_partial_stack` — `tests/items/ender_pearl/ender_pearl_throw_from_partial_stack.json`
- [ ] `farmland_drops_dirt_when_destroyed` — `tests/vegetation/farmland/farmland_drops_dirt_when_destroyed.json`
- [ ] `fern_explosion_drops_no_fern` — `tests/vegetation/fern/fern_explosion_drops_no_fern.json`
- [ ] `fishing_rod_cast_keeps_rod` — `tests/items/fishing_rod/fishing_rod_cast_keeps_rod.json`
- [ ] `furnace_cooking_progress_advances` — `tests/container/furnace/furnace_cooking_progress_advances.json`
- [ ] `furnace_cooking_progress_cools_down` — `tests/container/furnace/furnace_cooking_progress_cools_down.json`
- [ ] `furnace_different_result_item_blocks_smelting` — `tests/container/furnace/furnace_different_result_item_blocks_smelting.json`
- [ ] `furnace_explosion_drops_self_and_contents` — `tests/container/furnace/furnace_explosion_drops_self_and_contents.json`
- [ ] `furnace_fuel_burns_out` — `tests/container/furnace/furnace_fuel_burns_out.json`
- [ ] `furnace_fuel_without_input_not_consumed` — `tests/container/furnace/furnace_fuel_without_input_not_consumed.json`
- [ ] `furnace_full_result_slot_blocks_smelting` — `tests/container/furnace/furnace_full_result_slot_blocks_smelting.json`
- [ ] `furnace_lava_bucket_leaves_empty_bucket` — `tests/container/furnace/furnace_lava_bucket_leaves_empty_bucket.json`
- [ ] `furnace_smelts_raw_iron` — `tests/container/furnace/furnace_smelts_raw_iron.json`
- [ ] `furnace_unsmeltable_input_not_cooked` — `tests/container/furnace/furnace_unsmeltable_input_not_cooked.json`
- [ ] `gold_ore_explosion_drops_raw_gold` — `tests/world/gold_ores/gold_ore_explosion_drops_raw_gold.json`
- [ ] `grass_block_explosion_drops_dirt` — `tests/vegetation/grass_block/grass_block_explosion_drops_dirt.json`
- [ ] `gravel_explosion_drops_one_item` — `tests/gravity/gravel/gravel_explosion_drops_one_item.json`
- [ ] `grindstone_explosion_drops_item` — `tests/decoration/grindstone/grindstone_explosion_drops_item.json`
- [ ] `hanging_roots_destroyed_by_explosion` — `tests/vegetation/hanging_roots/hanging_roots_destroyed_by_explosion.json`
- [ ] `hay_block_explosion_drops_itself` — `tests/decoration/hay_block/hay_block_explosion_drops_itself.json`
- [ ] `heavy_core_survives_tnt_explosion` — `tests/decoration/heavy_core/heavy_core_survives_tnt_explosion.json`
- [ ] `heavy_weighted_pressure_plate_power_levels` — `tests/redstone/pressure_plate/heavy_weighted_pressure_plate_power_levels.json`
- [ ] `hoe_breaks_after_32_tills` — `tests/items/hoe/hoe_breaks_after_32_tills.json`
- [ ] `iron_ore_tnt_drops_raw_iron` — `tests/world/iron_ore/iron_ore_tnt_drops_raw_iron.json`
- [ ] `jack_o_lantern_tnt_explosion_drops_item` — `tests/decoration/jack_o_lantern/jack_o_lantern_tnt_explosion_drops_item.json`
- [ ] `jukebox_explosion_drops_itself` — `tests/redstone/jukebox/jukebox_explosion_drops_itself.json`
- [ ] `lapis_ore_explosion_drops_lapis_lazuli` — `tests/world/lapis_ores/lapis_ore_explosion_drops_lapis_lazuli.json`
- [ ] `lapis_ore_explosion_drops_no_experience` — `tests/world/lapis_ores/lapis_ore_explosion_drops_no_experience.json`
- [ ] `lava_cauldron_interactions` — `tests/decoration/cauldrons/lava_cauldron_interactions.json`
- [ ] `nether_gold_ore_explosion_drops_gold_nugget` — `tests/world/gold_ores/nether_gold_ore_explosion_drops_gold_nugget.json`
- [ ] `oak_pressure_plate_stays_pressed` — `tests/redstone/pressure_plate/oak_pressure_plate_stays_pressed.json`
- [ ] `oak_sign_ink_wax_and_click_commands` — `tests/decoration/signs/oak_sign_ink_wax_and_click_commands.json`
- [ ] `oak_stairs_furnace_fuel` — `tests/decoration/stairs/oak_stairs_furnace_fuel.json`
- [ ] `powder_snow_cauldron_interactions` — `tests/decoration/cauldrons/powder_snow_cauldron_interactions.json`
- [ ] `shovel_breaks_after_32_flattens` — `tests/items/shovel/shovel_breaks_after_32_flattens.json`
- [ ] `shovel_failed_uses_cost_no_durability` — `tests/items/shovel/shovel_failed_uses_cost_no_durability.json`
- [ ] `stairs_corner_between_materials` — `tests/connectible/stairs/stairs_corner_between_materials.json`
- [ ] `stairs_corner_neighbor_update` — `tests/connectible/stairs/stairs_corner_neighbor_update.json`
- [ ] `stairs_corner_placement` — `tests/connectible/stairs/stairs_corner_placement.json`
- [ ] `stairs_shape_vertical_update` — `tests/connectible/stairs/stairs_shape_vertical_update.json`
- [ ] `tnt_explosion_drops_honey_block` — `tests/decoration/honey_block/tnt_explosion_drops_honey_block.json`
- [ ] `water_cauldron_buckets` — `tests/decoration/cauldrons/water_cauldron_buckets.json`
- [ ] `waxed_lightning_rod_explosion_drops_self` — `tests/redstone/lightning_rods/waxed_lightning_rod_explosion_drops_self.json`
- [ ] `wooden_axe_furnace_fuel` — `tests/items/axes/wooden_axe_furnace_fuel.json`

## Flaky (20) — failed in some runs

- [ ] `crimson_stem_survives_fire` — `tests/world/crimson_stem/crimson_stem_survives_fire.json` (2/3)
- [ ] `lava_blue_ice_requires_soul_soil` — `tests/fluids/lava/lava_blue_ice_requires_soul_soil.json` (2/3)
- [ ] `lava_ignites_hanging_signs` — `tests/decoration/signs/lava_ignites_hanging_signs.json` (2/3)
- [ ] `lava_ignites_standing_signs` — `tests/decoration/signs/lava_ignites_standing_signs.json` (2/3)
- [ ] `lava_ignites_wall_hanging_signs` — `tests/decoration/signs/lava_ignites_wall_hanging_signs.json` (2/3)
- [ ] `lava_ignites_wall_signs` — `tests/decoration/signs/lava_ignites_wall_signs.json` (2/3)
- [ ] `shovel_ignores_unflattenable_blocks` — `tests/items/shovel/shovel_ignores_unflattenable_blocks.json` (2/3)
- [ ] `bamboo_age_propagation` — `tests/vegetation/bamboo/bamboo_age_propagation.json` (1/3)
- [ ] `bamboo_bonemeal_middle_of_column` — `tests/vegetation/bamboo/bamboo_bonemeal_middle_of_column.json` (1/3)
- [ ] `bamboo_stacking_on_sapling` — `tests/vegetation/bamboo/bamboo_stacking_on_sapling.json` (1/3)
- [ ] `bed_sleep_skips_night` — `tests/decoration/beds/bed_sleep_skips_night.json` (1/3)
- [ ] `copper_grate_oxidizes_over_time` — `tests/decoration/copper_grates/copper_grate_oxidizes_over_time.json` (1/3)
- [ ] `copper_stairs_honeycomb` — `tests/decoration/stairs/copper_stairs_honeycomb.json` (1/3)
- [ ] `copper_stairs_scrape` — `tests/decoration/stairs/copper_stairs_scrape.json` (1/3)
- [ ] `exposed_bulb_oxidizes_over_time` — `tests/redstone/copper_bulb/exposed_bulb_oxidizes_over_time.json` (1/3)
- [ ] `exposed_copper_bars_oxidize_randomly` — `tests/connectible/bars/exposed_copper_bars_oxidize_randomly.json` (1/3)
- [ ] `exposed_copper_lantern_oxidizes` — `tests/decoration/lanterns/exposed_copper_lantern_oxidizes.json` (1/3)
- [ ] `honeycomb_dispenser_waxes_copper_block` — `tests/items/honeycomb/honeycomb_dispenser_waxes_copper_block.json` (1/3)
- [ ] `jack_o_lantern_spawns_copper_golem` — `tests/decoration/jack_o_lantern/jack_o_lantern_spawns_copper_golem.json` (1/3)
- [ ] `lantern_destroyed_by_piston` — `tests/decoration/lanterns/lantern_destroyed_by_piston.json` (1/3)

Rerun one: `~/flint/FlintCLI/target/release/flintmc <file> -s localhost:25565`
