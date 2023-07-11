<div align="center">

   # **R3nzSkin**

   ## Announcement

   <img src="https://user-images.githubusercontent.com/58574988/134170370-c827d712-fcc7-432f-b9f8-96678b0c9bf6.gif">

   `R3nzSkin` is internal skin changer for League of Legends.

</div>

- Change the skin of your champion, your ward, other champions, towers, minions and jungle monsters in the game.
- Automatic skins database update.
- Support for spectator mode.
- Change skins anytime and unlimited times in single game.
- Supports all Popular languages ​​in the world.
- In-game configuration with <a href="https://github.com/ocornut/imgui">ImGui</a>.
- <a href="https://github.com/nlohmann/json">JSON</a> based configuration saving & loading

# Usage
   1. Compile source or <a href="https://github.com/Darkrai98/R3nzSkin/releases/latest">download</a> compiled version.
   2. Use `R3nzSkin_Injector` or inject the resulting DLL into the game yourself.
      - *Administrator* privilege may be needed if failed to inject.
      - League client can crash if injected before going into arena.
         - A workaround is to not inject until you are in the arena (you will need to be fast to not disrupt the game).
   3. Press <kbd>Insert</kbd> to bring up the menu.
   4. Select skin for you, your teammates, enemies, wards.

# Further optimizations
   If your CPU supports AVX / AVX2 / AVX-512 instruction set, you can enable it in project settings. This should result in more performant code, optimized for your CPU. Currently SSE2 instructions are selected in project settings.

# Credits
   This program is an improved and updated version of the <a href="https://github.com/B3akers">B3akers</a>/<a href="https://github.com/B3akers/LeagueSkinChanger">LeagueSkinChanger</a> project.
