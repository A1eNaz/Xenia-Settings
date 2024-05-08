# test

This is a test.

test

---

## Config Settings for Games/Apps

Why do my XBLA games play on trial mode?</br>
Why do my DLCs not work?
- license_mask = 1

| Game | Notes | Patches/Plugins | Recommended TUs | Netplay Compatibility
|---|---|---|---|---|
| Aurora Dashboard | allow_game_relative_writes = true</br>protect_zero = false</br>gpu_allow_invalid_fetch_constants = true | | | No
| Battlefield: Bad Company | d3d12_readback_resolve = true | | Base | No
| Borderlands 2 | [PLAY ON MASTER]<br>vsync = false | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Call of Duty: Advanced Warfare | d3d12_readback_resolve = true</br>protect_zero = false | | TU 17 | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Counter-Strike: Global Offensive | break_on_unimplemented_instructions = false</br>clear_memory_page_state = true | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Dead or Alive 4 | clear_memory_page_state = true | | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Fight Night Champion | create a 00000002 in it's content folder<br>d3d12_readback_resolve = true<br>mount_cache = true<br>mount_scratch = true<br>vsync = false<br>clear_memory_page_state = true<br>apu_max_queued_frames = 3 | [Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/45410915%20-%20Fight%20Night%20Champion%20(TU0).patch.toml)<br>[TU 1 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/45410915%20-%20Fight%20Night%20Champion%20(TU1).patch.toml)<br>[TU 2 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/45410915%20-%20Fight%20Night%20Champion%20(TU2).patch.toml) | Base | No
| Forza Horizon | mount_cache = true | [Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/4D5309C9%20-%20Forza%20Horizon.patch.toml) | Base | No
| Grand Theft Auto IV | gpu = vulkan | [Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/545407F2%20-%20Grand%20Theft%20Auto%20IV.patch.toml)<br>[TU 8 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/545407F2%20-%20Grand%20Theft%20Auto%20IV%20(TU8).patch.toml) | TU 8 | No
| Grand Theft Auto: Episodes from Liberty City | gpu = vulkan | | Base | No
| Gundam Operation Troy | ender_target_path_d3d12 = "rov" | [English Patch](https://github.com/Eight-Mansions/MSGOT/releases) | TU 1 | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Grand Theft Auto V | query_occlusion_fake_sample_count = -1<br>query_occlusion_fake_sample_count = 1000 | [TU 26 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/545408A7%20-%20Grand%20Theft%20Auto%20V%20(TU26).patch.toml)<br>[TU 27 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/545408A7%20-%20Grand%20Theft%20Auto%20V%20(TU27).patch.toml) | TU 26 | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Kane & Lynch 2: Dog Days | d3d12_readback_resolve = true | | TU 1 | No
| Left 4 Dead | d3d12_readback_resolve = true<br>cl = "-dvd -novid" | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Left 4 Dead 2 | d3d12_readback_resolve = true<br>cl = "mat_motion_blur_percent_of_screen_max 0" | [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) | Base | [Yes](https://github.com/AdrianCassar/xenia-canary/tree/netplay_canary_experimental_readme?tab=readme-ov-file#netplay-fork)
| Mass Effect 1 | internal_display_resolution: 2-5<br>use_new_decoder = true | | Base | No
| Metal Gear Solid HD Collection | gpu_allow_invalid_fetch_constants = true<br>cl = "MGS2.xex"<br>cl = "MGS3.xex" | | Base | No
| Metal Gear Solid V | d3d12_readback_resolve = true<br>no_discard_stencil_in_transfer_pipelines = true<br>native_stencil_value_output_d3d12_intel = true | | Base | No
| Minecraft | vsync = false<br>mount_cache = true | [Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/584111F7%20-%20Minecraft%20(XBLA%2C%20TU0).patch.toml)<br>[TU 1 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/584111F7%20-%20Minecraft%20(XBLA%2C%20TU1).patch.toml)<br>[TU 2 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/584111F7%20-%20Minecraft%20(XBLA%2C%20TU2).patch.toml)<br>[TU 3 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/584111F7%20-%20Minecraft%20(XBLA%2C%20TU3).patch.toml)<br>[TU 4 Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/584111F7%20-%20Minecraft%20(XBLA%2C%20TU4).patch.toml)
| Operation Darkness | use_fuzzy_alpha_epsilon = false | | Base | No