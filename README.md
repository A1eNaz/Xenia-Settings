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
