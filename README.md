# Xenia Config Settings for Games

Where do i download the latest canary from?
- You download it from [here](https://github.com/xenia-canary/xenia-canary/releases/download/experimental/xenia_canary.zip) or this [link](https://github.com/xenia-canary/xenia-canary/releases)

How do i play games on Xenia with Online Support?
- You can get it from this [link.](https://github.com/AdrianCassar/xenia-canary/wiki)

How do i use Mouse & Keyboard for Xenia?
- From this [link](https://github.com/marinesciencedude/xenia-canary-mousehook) but only a few games have Mouse Support.
You can make your own Keybinds with this method in the bindings.ini file:<br>
[Media ID - Game Name]<br>
Keybind = Controller Bind<br>
[eg. W = LS-Up]

How do i play games with 2 discs?
- Can't be bothered to write a guide so just follow Sowa_95's video: https://youtube.com/clip/Ugkx4hDbFhE9AKnRKHwOR_1TrCWK-DnulaZd?si=sc6Ufgx4BSl1h2_C

Where do i obtain Game Patches from?
- You can obtain Game [Patches](https://github.com/xenia-canary/game-patches/releases/latest/download/game-patches.zip) from here or from this [link.](https://github.com/xenia-canary/game-patches)

Some games don't have a 60/Unlocked FPS Patch.
- Either wait for a patch or use [Lossless Scaling](https://store.steampowered.com/app/993090/Lossless_Scaling/) with this [config](https://github.com/joever2022/test/blob/main/LS%20Config.png) as an alternative for games that speedup with VSync. (costs 7 dollars tho.)

Are there achievements for Xenia?
- Kinda but it's merely cosmetic, it will be a full feature with progress tracking in the future.
This is how you enable it:<br>
show_achievement_notification = true<br>
notification_sound_path = "C:/Xenia/360 notification.wav"<br>
custom_font_path = "C:/Xenia/Conv.ttf"<br>
Must be with forward /<br>
[video](https://youtu.be/AWLHrMNl2CU) by Sowa_95 shows it in action with some games.

Why do my XBLA games play on Trial mode?</br>
Why do my DLCs not work?
- Change license_mask = 1 (or license_mask = -1) in the xenia config

---

## Games List

## CTRL+F then search.

| Game | Settings | Plugins | Recommended TUs | Netplay Compatibility
|---|---|---|---|---|
| 007: Blood Stone | d3d12_readback_resolve = true<br>disassemble_functions = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| 3D Ultra Minigolf | must be extracted in xex format | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| 50 Cent: Blood on the Sand | render_target_path_d3d12 = "rov"<br>vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Ace Combat 6 | ac6_ground_fix = true<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| Aegis Wing | must be extracted in xex format | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Alan Wake | d3d12_readback_resolve = true<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| Alan Wake's American Nightmare | d3d12_readback_resolve = true | | Base | No
| Aliens: Colonial Marines | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Alien: Isolation | d3d12_readback_resolve = true<br>mount_cache = true | | Base | No
| Apache: Air Assault | d3d12_readback_resolve = true | | Base | No
| Armored Core V | protect_zero = false<br>d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Armored Core: Verdict Day | protect_zero = false<br>d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Army of Two | internal_display_resolution = 4<br>scribble_heap = true<br>query_occlusion_fake_sample_count = -1 | | Base | No
| Army of Two: The 40th Day | vsync = false<br>framerate_limit = 0 | | Base | No
| Aurora Dashboard | allow_game_relative_writes = true</br>protect_zero = false</br>gpu_allow_invalid_fetch_constants = true | | Base | No
| Banjo-Kazooie | internal_display_resolution = 16 | | Base | No
| Banjo Kazooie: Nuts & Bolts | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Banjo-Tooie | internal_display_resolution = 16 | | Base | No
| Batman: Arkham Asylum | internal_display_resolution = 4 | | Base | No
| Battlefield: Bad Company | d3d12_readback_resolve = true | | Base | No
| Battle vs. Chess | d3d12_readback_resolve = true | | Base | No
| Bare Knuckle | | | TU 2 | No
| Beautiful Katamari | protect_zero = false<br>scribble_heap = true<br>writable_executable_memory = true | | Base | No
| Beyond Good & Evil HD | d3d12_readback_resolve = true<br>query_occlusion_fake_sample_count = -1 | | Base | No
| BioShock 2 | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Birds of Steel | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Blackwater | protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Blazing Angels 2 | protect_zero = false | | Base | No
| Bloody Good Time | d3d12_readback_resolve = true<br>break_on_unimplemented_instructions = false | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Blue Dragon | clear_memory_page_state = true<br>apu_max_queued_frames = 16 | | Base | No
| Blur | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Bodycount | query_occlusion_fake_sample_count = -1 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Borderlands | vsync = false<br>framerate_limit = 0<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Borderlands 2 | vsync = false<br>framerate_limit = 0<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Brothers in Arms: Hell's Highway | render_target_path_d3d12 = "rov" | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Bulletstorm | render_target_path_d3d12 = "rov" | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Call of Duty: Advanced Warfare | d3d12_readback_resolve = true<br>protect_zero = false<br>controller_hotkeys = true | | TU 17 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Call of Duty: Classic | protect_zero = false | | Base | No
| Call of Duty: Modern Warfare | cl = "r_vsync 0" | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Call of Duty: Modern Warfare 2 | cl = "+r_vsync 0 +com_maxfps 0" | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Call of Duty: Modern Warfare 3 | cl = "r_vsync 0"<br><br>Netplay Config:<br>allow_plugins = true | [System Link](https://raw.githubusercontent.com/A1eNaz/Xenia-Game-Settings/main/Game%20FIles/MW3SystemLink.zip) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Castlevania: Harmony of Despair | internal_display_resolution = 16 | | Base | No
| Condemned | use_dedicated_xma_thread = false<br>use_new_decoder = true<br> | [Unlocked FPS + Extended FOV](https://raw.githubusercontent.com/A1eNaz/Xenia-Game-Settings/main/Game%20FIles/Condemned%20FPS%20%2B%20FOV.zip) | Base | No
| Conflict: Denied Ops | d3d12_readback_resolve = true | | Base | No
| Counter-Strike: Global Offensive | break_on_unimplemented_instructions = false</br>clear_memory_page_state = true | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Crackdown | use_dedicated_xma_thread = false<br>use_new_decoder = true<br>d3d12_readback_resolve = true<br>controller_hotkeys = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Crysis 3 | d3d12_readback_resolve = true<br>gpu_allow_invalid_fetch_constants = true | | Base | No
| Damnation | protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Dark Messiah of Might & Magic Elements | query_occlusion_fake_sample_count = -1<br>d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Dark Souls | d3d12_readback_resolve = true<br>use_dedicated_xma_thread = false<br>use_new_decoder = true<br>query_occlusion_fake_sample_count = -1 | | Base | No
| Dark Souls 2 | d3d12_readback_resolve = true<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| DAYTONA USA | internal_display_resolution = 16 | | Base | No
| Dead or Alive 4 | apu_max_queued_frames = 16<br>use_new_decoder = true<br>use_dedicated_xma_thread = false<br>clear_memory_page_state = true<br>gpu_allow_invalid_fetch_constants = true<br>draw_resolution_scale_x = 2<br>draw_resolution_scale_y = 2<br><br>Netplay Config:<br>protect_zero = false<br>vsync = false<br>framerate_limit = 120 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Deadpool | [FPS and Lens Flare Fix](https://raw.githubusercontent.com/A1eNaz/Xenia-Game-Settings/main/Game%20FIles/Deadpool.zip) | | Base | No
| Dead Rising | clear_memory_page_state = true<br> render_target_path_d3d12 = "rov"<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| DeathSpank | protect_zero = false | | Base | No
| DiRT | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| DiRT 3 | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| DiRT Showdown | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Dragon Ball Raging Blast 2 | draw_resolution_scale_x = 2<br>draw_resolution_scale_y = 2 | | Base | No
| DRIVER: San Francisco | vsync = false<br>framerate_limit = 0 | | Base | No
| Dungeons & Dragons: Daggerdale | protect_zero = false | | Base | No
| ESCHATOS | render_target_path_d3d12 = "rov" | | Base | No
| F1 2010 | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| F1 2011 | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| F1 2013 | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Fable 2 | clear_memory_page_state = true | | Base | No
| Fable Heroes | d3d12_readback_resolve = true | | Base | No
| Far Cry 3 | scribble_heap = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Far Cry 3 Blood Dragon | scribble_heap = true<br>vsync = false<br>framerate_limit = 0<br>query_occlusion_fake_sample_count = -1 | | Base | No
| FIFA 14 | d3d12_readback_resolve = true<br>clear_memory_page_state = true | | Base | No
| FIFA 15 | d3d12_readback_resolve = true<br>clear_memory_page_state = true<br>disassemble_functions = true | | Base | No
| FIFA 17 | clear_memory_page_state = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| FIFA 19 | d3d12_readback_resolve = true<br>clear_memory_page_state = true | | Base | No
| FIFA Street 3 | Internal_display_resolution = 16 | | Base | No
| Fight Night Champion | create a 00000002 in the content folder<br>d3d12_readback_resolve = true<br>mount_cache = true<br>mount_scratch = true<br>vsync = false<br>framerate_limit = 0<br>clear_memory_page_state = true<br>apu_max_queued_frames = 3 | | Base | No
| FlatOut: Ultimate Carnage | vsync = false<br>framerate_limit = 0<br>query_occlusion_fake_sample_count = -1 | | Base | No
| Forza Horizon | mount_cache = true<br>gpu_allow_invalid_fetch_constants = true<br>framerate_limit = 0 | | Base | No
| Forza Horizon 2 | mount_cache = true<br>d3d12_readback_resolve = true<br>gpu_allow_invalid_fetch_constants = true | | Base | No
| Forza Motorsport 2 | mount_cache = true<br>query_occlusion_fake_sample_count = -1 | | Base | No
| Forza Motorsport 3 | use_new_decoder = true<br>use_dedicated_xma_thread = false<br>query_occlusion_fake_sample_count = -1<br>mount_cache = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Forza Motorsport 4 | [2022 Build](https://raw.githubusercontent.com/joever2022/test/main/xenia_canary.exe)<br>mount_cache = true<br>query_occlusion_fake_sample_count = -1<br>d3d12_readback_resolve = true<br>use_new_decoder = true<br>use_dedicated_xma_thread = false<br>gpu_allow_invalid_fetch_constants = true | [Project Forza Plus](https://www.reddit.com/r/ProjectForzaPlus/comments/11a4qus/welcome_to_the_project_forza_plus_sub/) | Base | No
| Freefall Racers | protect_zero = false | | Base | No
| Frontlines: Fuel of War | protect_zero = false<br>vsync = false<br>framerate_limit = 0<br>disassemble_functions = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Fuse | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Gears of War | vsync = false<br>framerate_limit = 0<br>[Black Shading Fix](https://github.com/xenia-canary/game-patches/blob/main/patches/4D5307D5%20-%20Gears%20of%20War.patch.toml)<br>[Black Shading Fix TU5](https://github.com/xenia-canary/game-patches/blob/main/patches/4D5307D5%20-%20Gears%20of%20War.patch.toml) | | TU 5 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Gears of War 2 | vsync = false<br>framerate_limit = 0<br>[Black Shading Fix](https://github.com/xenia-canary/game-patches/blob/main/patches/4D53082D%20-%20Gears%20of%20War%202.patch.toml)<br>[Black Shading Fix TU6](https://github.com/xenia-canary/game-patches/blob/main/patches/4D53082D%20-%20Gears%20of%20War%202%20(TU6).patch.toml) | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Gears of War 3 | protect_zero = false<br>vsync = false<br>framerate_limit = 0 | [Extended FOV](https://raw.githubusercontent.com/A1eNaz/Xenia-Game-Settings/main/Game%20FIles/GoW3%20Extended%20FOV.zip) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Gears of War: Judgment | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Geometry Wars: Retro Evolved | apu_max_queued_frames = 16<br>use_new_decoder = true<br>use_dedicated_xma_thread = false | | Base | No
| Geometry Wars: Retro Evolved 2 | apu_max_queued_frames = 16<br>use_dedicated_xma_thread = false<br>internal_display_resolution = 16 | | Base | No
| Geometry Wars 3: Dimensions | apu_max_queued_frames = 16<br>use_new_decoder = true<br>use_dedicated_xma_thread = false | | Base | No
| Ghost Recon Advanced Warfighter 2 | vsync = false<br>framerate_limit = 0 | | TU 4 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Ghost Recon: Future Soldier | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| GoldenEye: 007 Reloaded | query_occlusion_fake_sample_count = -1 | | Base | No
| GoldenEye XBLA | | [Community Edition Updater](http://n64vault.com/ge-xbla-tools:community-edition-updater)<br>[Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Grand Theft Auto IV | gpu = vulkan | | TU 8 | No
| Grand Theft Auto: Episodes from Liberty City | gpu = vulkan | | Base | No
| Grand Theft Auto V | d3d12_readback_resolve = true<br>protect_zero = false<br>query_occlusion_fake_sample_count = -1 (Fixes Sun Flare clipping)<br>query_occlusion_fake_sample_count = 1000 (Makes Phone Camera work) | [No Water Waves TU 26](https://drive.google.com/file/d/1-d8NAPTyP3tRXYhFJrjfyGFOIeAcfupY/view) | TU 26 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| GRID 2 | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| GUILTY GEAR 2 | d3d12_readback_resolve = true | | Base | No
| Gundam Operation Troy | render_target_path_d3d12 = "rov" | [English Patch](https://github.com/Eight-Mansions/MSGOT/releases) | TU 1 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Halo 3 |  | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | V13.2 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Halo 3 ODST |  | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | No
| Halo 4 | d3d12_readback_resolve = true<br>query_occlusion_fake_sample_count = -1 | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | No
| Halo Reach | query_occlusion_fake_sample_count = -1 | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | No
| Hitman: Absolution | protect_zero = false<br>d3d12_readback_resolve = true | | Base | No
| Hydro Thunder Hurricane | d3d12_readback_resolve = true | | Base | No
| Kameo: Elements of Power | use_dedicated_xma_thread = false<br>use_new_decoder = true | | TU 2 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Kane & Lynch 2: Dog Days | d3d12_readback_resolve = true | | TU 1 | No
| Left 4 Dead | d3d12_readback_resolve = true<br>cl = "-dvd -novid"<br>query_occlusion_fake_sample_count = -1<br>break_on_unimplemented_instructions = false | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Left 4 Dead 2 | d3d12_readback_resolve = true<br>cl = "mat_motion_blur_percent_of_screen_max 0"<br>break_on_unimplemented_instructions = false | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook)<br>[Unlock FPS](https://raw.githubusercontent.com/A1eNaz/Xenia-Game-Settings/main/Game%20FIles/L4D2%20Unlock%20FPS.zip) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Lost Odyssey | vsync = false<br>framerate_limit = 0<br>draw_resolution_scale_x = 2<br>draw_resolution_scale_y = 2<br>apu_max_queued_frames = 16<br>render_target_path_d3d12 = "rov" | | Base | No
| Madagascar: Escape 2 Africa | d3d12_readback_resolve = true | | Base | No
| Madden NFL 11 | mount_cache = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Madden NFL 13 | mount_cache = true | | Base | No
| Madden NFL 25 | d3d12_readback_resolve = true<br>mount_cache = true | | Base | No
| Mafia II | protect_zero = false<br>query_occlusion_fake_sample_count = -1 | | Base | No
| Marvel Ultimate Alliance | protect_zero = false<br>query_occlusion_fake_sample_count = -1<br>vsync = false<br>framerate_limit = 0<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Mass Effect 1 | internal_display_resolution: 2-5<br>use_new_decoder = true | | Base | No
| Max: The Curse of Brotherhood | protect_zero = false<br>break_on_unimplemented_instructions = false | | Base | No
| Metal Gear Solid HD Collection | gpu_allow_invalid_fetch_constants = true<br>apu_max_queued_frames = 16 [MGS2]<br>cl = "MGS2.xex"<br>cl = "MGS3.xex" | | Base | No
| Metal Gear Solid V | d3d12_readback_resolve = true<br>no_discard_stencil_in_transfer_pipelines = true<br>native_stencil_value_output_d3d12_intel = true | | Base | No
| Midnight Club: Los Angeles | query_occlusion_fake_sample_count = -1<br>framerate_limit = 120 | | Base | No
| Minecraft | vsync = false<br>framerate_limit = 0<br>mount_cache = true | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | No
| Mirror's Edge | [Shadow Shading Fix](https://github.com/xenia-canary/game-patches/blob/main/patches/45410850%20-%20Mirror's%20Edge.patch.toml) | | Base | No
| Monkey Island: SE | internal_display_resolution = 16 | | Base | No
| Monkey Island 2: SE | internal_display_resolution = 16<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Monster Madness: Battle for Suburbia | protect_zero = false<br>scribble_heap = true | | Base | No
| Murdered: Soul Suspect | query_occlusion_fake_sample_count = -1 | | Base | No
| MX vs. ATX Alive | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Naruto: The Broken Bond | clear_memory_page_state = true | | Base | No
| NASCAR 15: Victory Edition | d3d12_readback_resolve = true<br>gpu_allow_invalid_fetch_constants = true | | Base | No
| NBA Street Homecourt | internal_display_resolution = 16 | | Base | No
| Need for Speed: Carbon | use_dedicated_xma_thread = false<br>use_new_decoder = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Need for Speed: Most Wanted 2005 | use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| Need for Speed: Most Wanted 2012 | d3d12_readback_memexport = true | | Base | No
| Need for Speed: Pro Street | use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | No
| NHL 11 | protect_zero = false<br>disassemble_functions = true | | Base | No
| NieR | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Nier Gestalt | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| NINJA BLADE | d3d12_readback_resolve = true<br>use_fuzzy_alpha_epsilon = true | | Base | No
| Ninja Gaiden II | protect_zero = false<br>clear_memory_page_state = true<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | [Skip Chapter 12 Crash TU 3](https://github.com/A1eNaz/Xenia-Game-Settings/blob/main/Patches/544307D5%20-%20Ninja%20Gaiden%20II%20(Japan%2C%20TU3).patch.toml) | Base | No
| Operation Darkness | use_fuzzy_alpha_epsilon = false | | Base | No
| Perfect Dark | [Shading Fix](https://github.com/xenia-canary/game-patches/blob/main/patches/584109C2%20-%20Perfect%20Dark.patch.toml)<br>[Shading Fix TU3](https://github.com/xenia-canary/game-patches/blob/main/patches/584109C2%20-%20Perfect%20Dark%20(TU3).patch.toml)<br>query_occlusion_fake_sample_count = -1<br>internal_display_resolution = 16 | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| PAYDAY 2 | vsync = false<br>framerate_limit = 0 | | TU 1 | No
| Panzer General: Allied Assault | d3d12_readback_resolve = true<br>clear_memory_page_state = true | | Base | No
| Pid | break_on_unimplemented_instructions = false<br>protect_zero = false | | Base | No
| Pinball FX | internal_display_resolution = 16 | | Base | No
| Portal | d3d12_readback_resolve = true<br>break_on_unimplemented_instructions = false<br>query_occlusion_fake_sample_count = -1<br>cl = "-dvd -game portal" | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | No
| Portal 2 | d3d12_readback_resolve = true<br>query_occlusion_fake_sample_count = -1 | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Pro Evolution Soccer 2006 | | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Pro Evolution Soccer 2008 | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Pro Evolution Soccer 2009 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2010 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2011 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2012 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2013 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2014 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2015 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2016 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2017 | d3d12_readback_resolve = true | | Base | No
| Pro Evolution Soccer 2018 | d3d12_readback_resolve = true | | Base | No
| Quake 2 | internal_display_resolution = 16 | | Base | No
| Race Driver: Grid | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Rainbow Six: Vegas 2 | vsync = false<br>framerate_limit = 0<br>clear_memory_page_state = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Rayman Legends | internal_display_resolution = 16 | | Base | No
| Rayman Origins | internal_display_resolution = 16 | | Base | No
| Red Dead Redemption | [Unlock Social Club Content](https://github.com/joever2022/Xenia-Game-Settings/blob/main/RDR1%20Social%20Club.png)<br>vsync = false<br>framerate_limit = 0<br>query_occlusion_fake_sample_count = -1<br>no_discard_stencil_in_transfer_pipelines = true [Frees 5% GPU Usage (NVIDIA ONLY) ] | [Reality Redemption](https://gtaforums.com/topic/989469-rel-wip-rdr-reality-redemption-overhaul-project/) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Red Faction: Armageddon | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Red Faction: Guerrilla | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Red Johnson | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Resident Evil: Operation Raccoon City | d3d12_readback_resolve = true<br>query_occlusion_fake_sample_count = -1<br>vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Ridge Racer Unbounded | query_occlusion_fake_sample_count = -1<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Sacred 2: Fallen Angel | protect_zero = false<br>internal_display_resolution = 16 | | Base | No
| Saints Row | apu_max_queued_frames = 16<br>protect_zero = false | | TU 1 | not yet.
| Saints Row 2 | apu_max_queued_frames = 3<br>protect_zero = false<br>query_occlusion_fake_sample_count = -1 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Saints Row the Third | d3d12_readback_resolve = true<br>render_target_path_d3d12 = "rov"<br>protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | TU 4 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Saints Row IV | d3d12_readback_resolve = true<br>render_target_path_d3d12 = "rov"<br>protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | TU 7 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Saints Row: Gat out of Hell | d3d12_readback_resolve = true<br>render_target_path_d3d12 = "rov"<br>protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Scott Pilgrim vs. the World: The Game | internal_display_resolution = 16 | | TU 4 | No
| ScreamRide | d3d12_readback_resolve = true | | Base | No
| Sealife Safari | d3d12_readback_resolve = true | | Base | No
| Secret Service | d3d12_readback_resolve = true | | Base | No
| SEGA Superstar Tennis | use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Serious Sam HD: The First Encounter | d3d12_readback_resolve = true | | Base | No
| Silent Hill Downpour | render_target_path_d3d12 = "rov" | | Base | No
| Skate 3 | vsync = false<br>framerate_limit = 0 | | Base | No
| Slender: The Arrival | protect_zero = false<br>break_on_unimplemented_instructions = false<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Snoopy Flying Ace | render_target_path_d3d12 = "rov"<br>use_dedicated_xma_thread = false<br>use_new_decoder = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Sonic & All-Stars Racing Transformed | vsync = false<br>framerate_limit = 0<br>render_target_path_d3d12 = "rov" | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Sonic & SEGA All-Stars Racing | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Sonic Free Riders | gpu_allow_invalid_fetch_constants = true | [No Kinect](https://gamebanana.com/mods/456720) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Sonic the Hedgehog 4: Episode I | internal_display_resolution = 16 | | Base | No
| Sonic Unleashed | [Setup Guide](https://gamebanana.com/tuts/17062) | | TU 2 | No
| SOULCALIBUR II HD | clear_memory_page_state = true | | Base | No
| Spec Ops: The Line | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Spider-Man Web of Shadows | vsync = false<br>framerate_limit = 0 | | Base | No
| Splinter Cell: Double Agent | use_dedicated_xma_thread = false<br>use_new_decoder = true<br>protect_zero = false | | V7.0.1 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| SpongeBob HeroPants | protect_zero = false<br>break_on_unimplemented_instructions = false<br>render_target_path_d3d12 = "rov" | | Base | No
| SSX | d3d12_readback_resolve = true
| Star Wars: The Force Unleashed II | query_occlusion_fake_sample_count = -1<br>d3d12_readback_resolve = true<br>scribble_heap = true | | Base | No
| State of Decay | protect_zero = false | | Base | No
| Super Street Fighter 2 THD | internal_display_resolution = 16 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Supremacy MMA | protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | Base | No
| TEKKEN 6 | clear_memory_page_state = true<br>draw_resolution_scale_x = 2<br>draw_resolution_scale_y = 2<br><br>Netplay Config:<br>vsync = false<br>framerate_limit = 120 | | TU 3 | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| TEKKEN Tag Tournament 2 | protect_zero = false<br>draw_resolution_scale_x = 2<br>draw_resolution_scale_y = 2 | | Base | No
| Teenage Mutant Ninja Turtles | protect_zero = false | | Base | No
| Tenchu Z | protect_zero = false<br>scribble_heap = true<br>clear_memory_page_state = true<br>use_fuzzy_alpha_epsilon = true | | Base | No
| Test Drive Unlimited | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| The Club | protect_zero = false<br>vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| The Darkness | query_occlusion_fake_sample_count = -1<br>[Bloom Fix](https://github.com/xenia-canary/game-patches/blob/main/patches/545407EE%20-%20The%20Darkness.patch.toml)<br>vsync = false<br>framerate_limit = 0  | | Base | No
| The Orange Box | query_occlusion_fake_sample_count = -1<br>d3d12_readback_resolve = true<br>cl = "-dvd -game hl2"<br>cl = "-dvd -game episodic"<br>cl = "-dvd -game ep2"<br>cl = "-dvd -game tf"<br>cl = "-dvd -game portal" | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| The Peanuts Movie: Snoopy's Grand Adventure | protect_zero = false<br>break_on_unimplemented_instructions = true | | Base | No
| The Witcher 2: Assassins of Kings | vsync = false<br>framerate_limit = 0 | | Base | No	
| Tiger Woods PGA Tour 08 | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Tiger Woods PGA Tour 09 | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| Titanfall | don't play this<br>query_occlusion_fake_sample_count = -1<br>d3d12_readback_resolve = true | | Base | No
| Tomb Raider Underworld | protect_zero = false<br>render_target_path_d3d12 = "rov" | | Base | No
| Top Spin 2 | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Trials HD | d3d12_readback_resolve = true | | Base | No
| UFC Undisputed 3 | gpu_allow_invalid_fetch_constants = true<br>d3d12_readback_resolve = true | | Base | No
| Ultra Street Fighter IV | vsync = false<br>framerate_limit = 0 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Virtua Tennis 3 | internal_display_resolution = 16 | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Viva Piñata: Trouble in Paradise | d3d12_readback_resolve = true (Terrible FPS but Fixes Ingame Screenshots)<br>scribble_heap = true | | Base | No
| Way of the Dogg | protect_zero = false<br>break_on_unimplemented_instructions = false | | Base | No
| WRC 2 | d3d12_readback_resolve = true | | Base | No
| WRC 3: FIA World Rally Championship | d3d12_readback_resolve = true<br>vsync = false<br>framerate_limit = 0 | | Base | No
| WRC 4: FIA World Rally Championship | d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| WWE 2K14 | gpu = vulkan<br>internal_display_resolution = 4<br>ignore_offset_for_ranged_allocations = true | | Base | No
| Zeno Clash UE | break_on_unimplemented_instructions = false<br>scribble_heap = true<br>d3d12_readback_resolve = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/wiki)
| Zoids Infinity EX Neo | protect_zero = false<br>clear_memory_page_state = truevsync = false<br>framerate_limit = 0 | | Base | No
| Zoo Tycoon | d3d12_readback_resolve = true | | Base | No