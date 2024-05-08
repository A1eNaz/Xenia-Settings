# test

This is a test.

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
| Grand Theft Auto IV | gpu = vulkan | [Patch](https://github.com/xenia-canary/game-patches/blob/main/patches/545407F2%20-%20Grand%20Theft%20Auto%20IV.patch.toml)<br>[TU 8 Patch]<https://github.com/xenia-canary/game-patches/blob/main/patches/545407F2%20-%20Grand%20Theft%20Auto%20IV%20(TU8).patch.toml> | TU 8 | No
| Grand Theft Auto: Episodes from Liberty City | gpu = vulkan | | Base | No