```
📂 Main folder
├──📂 assets
│  └──📂 minecraft
│     ├──📂 blockstates
│     │  └──📄 <block_id>.json (e.g. air.json)
│     │
│     ├──📂 font
│     │  ├──📄 alt.json
│     │  ├──📄 default.json
│     │  ├──📄 glyph_sizes.bin
│     │  ├──📄 illageralt.json
│     │  └──📄 uniform.json
│     │
│     ├──📂 lang
│     │  └──📄 <language_id>.json (e.g. en_us.json)
│     │ 
│     ├──📂 models
│     │  ├──📂 block
│     │  │  └──📄 <block_model_id>.json (e.g. acacia_fence_inventory.json)
│     │  │
│     │  └──📂 item
│     │     └──📄 <item_model_id>.json (e.g. stone_sword.json)
│     │
│     ├──📂 particles
│     │  └──📄 <particle_id>.json (e.g. ash.json)
│     │
│     ├──📂 shaders
│     │  └── might add
│     │
│     ├──📂 texts
│     │  ├──📄 credits.json
│     │  ├──📄 end.txt
│     │  ├──📄 postcredits.txt
│     │  └──📄 splashes.txt
│     │
│     └──📂 textures
│        ├──📂 block
│        │  └──🖼️ <block_id>.png (e.g. stone.png)
│        │
│        ├──📂 colormap
│        │  ├──🖼️ foliage.png 
│        │  └──🖼️ grass.png
│        │
│        ├──📂 effect
│        │  └──🖼️ dither.png
│        │
│        ├──📂 entity
│        │  ├──📂 <entity_id> (e.g. villager)
│        │  │  └──🖼️ (entity specific files) 
│        │  ├──🖼️ alex.png
│        │  ├──🖼️ banner_base.png
│        │  ├──🖼️ bat.png
│        │  ├──🖼️ beacon_beam.png
│        │  ├──🖼️ blaze.png
│        │  ├──🖼️ chicken.png
│        │  ├──🖼️ dolphin.png
│        │  ├──🖼️ elytra.png
│        │  ├──🖼️ enchanting_table_book.png
│        │  ├──🖼️ end_gateway_beam.png
│        │  ├──🖼️ end_portal.png
│        │  ├──🖼️ endermite.png
│        │  ├──🖼️ experience_orb.png
│        │  ├──🖼️ fishing_hook.png
│        │  ├──🖼️ guardian.png
│        │  ├──🖼️ guardian_beam.png
│        │  ├──🖼️ guardian_elder.png
│        │  ├──🖼️ lead_knot.png
│        │  ├──🖼️ minecart.png
│        │  ├──🖼️ phantom.png
│        │  ├──🖼️ phantom_eyes.png
│        │  ├──🖼️ shield_base.png
│        │  ├──🖼️ shield_base_nopattern.png
│        │  ├──🖼️ silverfish.png
│        │  ├──🖼️ snow_golem.png
│        │  ├──🖼️ spider_eyes.png
│        │  ├──🖼️ steve.png
│        │  ├──🖼️ trident.png
│        │  ├──🖼️ trident_riptide.png
│        │  ├──🖼️ wandering_trader.png
│        │  └──🖼️ witch.png
│        │
│        ├──📂 environment
│        │  ├──🖼️ clouds.png
│        │  ├──🖼️ end_sky.png
│        │  ├──🖼️ moon_phases.png
│        │  ├──🖼️ rain.png
│        │  ├──🖼️ snow.png
│        │  └──🖼️ sun.png
│        │
│        ├──📂 font
│        │  ├──🖼️ accented.png
│        │  ├──🖼️ ascii.png
│        │  ├──🖼️ ascii_sga.png
│        │  ├──🖼️ asciillager.png
│        │  ├──🖼️ nonlatin_european.png
│        │  └──🖼️ unicode_page_<00-ff>.png
│        │
│        ├──📂 gui
│        │  ├──📂 advancements
│        │  │  ├──📂 backgrounds
│        │  │  │  ├──🖼️ adventure.png
│        │  │  │  ├──🖼️ end.png
│        │  │  │  ├──🖼️ husbandry.png
│        │  │  │  ├──🖼️ nether.png
│        │  │  │  ├──🖼️ stone.png
│        │  │  │
│        │  │  ├──🖼️ tabs.png
│        │  │  ├──🖼️ widgets.png
│        │  │  └──🖼️ window.png
│        │  │
│        │  ├──📂 container
│        │  │  ├──📂 creative_inventory
│        │  │  ├──🖼️ anvil.png
│        │  │  ├──🖼️ beacon.png
│        │  │  ├──🖼️ blast_furnace.png
│        │  │  ├──🖼️ brewing_stand.png
│        │  │  ├──🖼️ bundle.png
│        │  │  ├──🖼️ cartography_table.png
│        │  │  ├──🖼️ crafting_table.png
│        │  │  ├──🖼️ dispenser.png
│        │  │  ├──🖼️ enchanting_table.png
│        │  │  ├──🖼️ furnace.png
│        │  │  ├──🖼️ gamemode_switcher.png
│        │  │  ├──🖼️ generic_54.png
│        │  │  ├──🖼️ grindstone.png
│        │  │  ├──🖼️ hopper.png
│        │  │  ├──🖼️ horse.png
│        │  │  ├──🖼️ inventory.png
│        │  │  ├──🖼️ loom.png
│        │  │  ├──🖼️ shulker_box.png
│        │  │  ├──🖼️ smithing.png
│        │  │  ├──🖼️ smoker.png
│        │  │  ├──🖼️ stats_icons.png
│        │  │  ├──🖼️ stonecutter.png
│        │  │  └──🖼️ villager2.png
│        │  │
│        │  ├──📂 presets
│        │  │  └──🖼️ isles.png
│        │  │ 
│        │  ├──📂 title
│        │  │  ├──📂 background
│        │  │  │  ├──🖼️ panorama_<0-5>.png
│        │  │  │  └──🖼️ panorama_overlay.png
│        │  │  │
│        │  │  ├──🖼️ edition.png
│        │  │  ├──🖼️ minecraft.png
│        │  │  └──🖼️ mojangstudios.png
│        │  │
│        │  ├──🖼️ accessibility.png
│        │  ├──🖼️ bars.png
│        │  ├──🖼️ book.png
│        │  ├──🖼️ checkbox.png
│        │  ├──🖼️ demo_background.png
│        │  ├──🖼️ icons.png
│        │  ├──🖼️ options_background.png
│        │  ├──🖼️ recipe_book.png
│        │  ├──🖼️ recipe_button.png
│        │  ├──🖼️ resource_packs.png
│        │  ├──🖼️ server_selection.png
│        │  ├──🖼️ social_interactions.png
│        │  ├──🖼️ stream_indicator.png
│        │  ├──🖼️ toasts.png
│        │  ├──🖼️ widgets.png
│        │  └──🖼️ world_selection.png
│        │
│        ├──📂 item
│        │  └──🖼️ <item_id>.png (e.g. apple.png)
│        │
│        ├──📂 map
│        │  ├──🖼️ map_background.png
│        │  ├──🖼️ map_background_checkerboard.png
│        │  └──🖼️ map_icons.png
│        │
│        ├──📂 misc
│        │  ├──🖼️ enchanted_item_glint.png
│        │  ├──📄 enchanted_item_glint.png.mcmeta
│        │  ├──🖼️ forcefield.png
│        │  ├──🖼️ nausea.png
│        │  ├──🖼️ powder_snow_outline.png
│        │  ├──🖼️ pumpkinblur.png
│        │  ├──📄 pumpkinblur.png.mcmeta
│        │  ├──🖼️ shadow.png
│        │  ├──📄 shadow.png.mcmeta
│        │  ├──🖼️ spyglass_scope.png
│        │  ├──🖼️ underwater.png
│        │  ├──🖼️ unknown_pack.png
│        │  ├──🖼️ unknown_server.png
│        │  ├──🖼️ vignette.png
│        │  ├──📄 vignette.png.mcmeta
│        │  └──🖼️ white.png
│        │
│        ├──📂 mob_effect
│        │  └──🖼️ <effect_id>.png (e.g. nausea.png)
│        │
│        ├──📂 models
│        │  └──📂 armor
│        │     ├──🖼️ chainmail_layer_<1-2>.png
│        │     ├──🖼️ diamond_layer_<1-2>.png
│        │     ├──🖼️ gold_layer_<1-2>.png
│        │     ├──🖼️ iron_layer_<1-2>.png
│        │     ├──🖼️ leather_layer_<1-2>.png
│        │     ├──🖼️ leather_layer_<1-2>_overlay.png
│        │     ├──🖼️ netherite_layer_<1-2>.png
│        │     └──🖼️ turtle_layer_1.png
│        │
│        ├──📂 painting (check paintings.md)
│        │  ├──🖼️ alban.png
│        │  ├──🖼️ aztec.png
│        │  ├──🖼️ aztec2.png
│        │  ├──🖼️ back.png
│        │  ├──🖼️ bomb.png
│        │  ├──🖼️ burning_skull.png
│        │  ├──🖼️ bust.png
│        │  ├──🖼️ courbet.png
│        │  ├──🖼️ creebet.png
│        │  ├──🖼️ donkey_kong.png
│        │  ├──🖼️ earth.png
│        │  ├──🖼️ fighters.png
│        │  ├──🖼️ fire.png
│        │  ├──🖼️ graham.png
│        │  ├──🖼️ kebab.png
│        │  ├──🖼️ match.png
│        │  ├──🖼️ pigscene.png
│        │  ├──🖼️ plant.png
│        │  ├──🖼️ pointer.png
│        │  ├──🖼️ pool.png
│        │  ├──🖼️ sea.png
│        │  ├──🖼️ skeleton.png
│        │  ├──🖼️ skull_and_roses.png
│        │  ├──🖼️ stage.png
│        │  ├──🖼️ sunset.png
│        │  ├──🖼️ void.png
│        │  ├──🖼️ wanderer.png
│        │  ├──🖼️ wasteland.png
│        │  ├──🖼️ water.png
│        │  ├──🖼️ wind.png
│        │  └──🖼️ wither.png
│        │
│        └──📂 particle
│           ├──🖼️ angry.png
│           ├──🖼️ big_smoke_<0-11>.png
│           ├──🖼️ bubble.png
│           ├──🖼️ bubble_pop_<0-4>.png
│           ├──🖼️ critical_hit.png
│           ├──🖼️ damage.png
│           ├──🖼️ drip_fall.png
│           ├──🖼️ drip_hang.png
│           ├──🖼️ drip_land.png
│           ├──🖼️ effect_<0-7>.png
│           ├──🖼️ enchanted_hit.png
│           ├──🖼️ explosion_<0-15>.png
│           ├──🖼️ flame.png
│           ├──🖼️ flash.png
│           ├──🖼️ generic_<0-7>.png
│           ├──🖼️ glint.png
│           ├──🖼️ glitter_<0-7>.png
│           ├──🖼️ glow.png
│           ├──🖼️ heart.png
│           ├──🖼️ lava.png
│           ├──🖼️ naulitius.png
│           ├──🖼️ note.png
│           ├──🖼️ sga_<a-z>.png (enchanting table letters)
│           ├──🖼️ soul_<0-10>.png
│           ├──🖼️ soul_fire_flame.png
│           ├──🖼️ spark_<0-7>.png
│           ├──🖼️ spell_<0-7>.png
│           ├──🖼️ splash_<0-3>.png
│           ├──🖼️ sweep_<0-7>.png
│           ├──🖼️ vibration.png
│           └──📄 vibration.png.mcmeta
│
├──📄 pack.mcmeta
└──🖼️ pack.png
```
