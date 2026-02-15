Versão em português [aqui](./README_ptbr.md)

# Insane Nights at Snowball’s — Remake

This repository contains an **independent remake** of the game **Insane Nights at Snowball’s**,  
based on the original source code published by **INaS Productions** under the **zlib license**.

This project is **unofficial**, **does not replace** the original project, and **does not claim authorship** of the original code.  
The purpose of this remake is **preservation**, **study**, and **creative continuation**, fully respecting the terms of the original license.

### About this remake
- Based on the original *Insane Nights at Snowball’s* source code  
- Developed as a **derivative project**  
- Modifications, improvements, and new technical or artistic decisions are the responsibility of this repository  
- The original code and authorship remain fully credited  

---

## Original Project (Original README below)

> **Note:**  
> The content below is the **original README**, preserved **without any modifications**, in accordance with the zlib license and out of respect for the original authors.

---

# Insane Nights at Snowball's

This is the source code of INaS. It was written in Lua using the [LÖVE framework](https://love2d.org). There is some messy code here and there, but feel free to use some some parts of the code on your own project (as long as you don't steal all the code and claim that you made it). If you want to use any of the renders, please contact the modeler: [Th3 Atomic](https://gamejolt.com/@Th3_Atomic_Official).

# Compilation

### Windows

1. Download the LÖVE executable [here](https://love2d.org) (32-bit is recommended, but 64-bit may work as well).

2. Extract all files somewhere or install if you downloaded the installer.

3. Clone or download this repository somewhere in your PC and zip it using any compression software. Make sure that all game files (especially "main.lua") are at the root of the archive, and not in a subfolder.

4. Rename the zip file to "inasgame.love" and move it to the same folder as the LÖVE executable.

5. Open the command prompt and type:

```bash
cd "path/to/love/folder"
copy /b love.exe+inasgame.love inas.exe
```

6. Create a new folder somewhere and copy the "inas.exe", "license.txt" and all the dll files to it.

7. Go to [Discord RPC repository](https://github.com/discord/discord-rpc) and compile or download a pre-compiled dll on "releases".

8. Move "discord-rpc.dll" to the same folder as "inas.exe".

### Other platforms

More information about compiling for other platforms in the [LÖVE wiki](https://love2d.org/wiki/Game_Distribution). Some changes in the code may be needed to make it compatible to all platforms.

# Credits

Programming: [FloatingBanana](https://gamejolt.com/@FloatingBanana)
Modelling: [Th3 Atomic](https://gamejolt.com/@Th3_Atomic_Official)

##### Libraries

* [Bump.lua](https://github.com/kikito/bump.lua)
* [lua-discordRPC](https://github.com/pfirsich/lua-discordRPC)
* [FPSGraph](https://github.com/icrawler/FPSGraph)
* [Gamejolt.lua](https://github.com/mbrovko/gamejoltlua)
* [HUMP](https://github.com/HDictus/hump/tree/temp-master)
* [Lily](https://github.com/MikuAuahDark/lily)
* [Lume](https://github.com/rxi/lume/)
* [Moonshine](https://github.com/vrld/moonshine)
* [Slab](https://github.com/coding-jackalope/Slab)
* [Kuey](https://love2d.org/wiki/Kuey)

##### Resources

* Jesús Lastra - [Abandoned](https://opengameart.org/content/collaboration-theme-song-abandoned)

* Anthon - [We are Safe](https://opengameart.org/content/we-are-safe)

* Scocapex - [Dark ambiance](https://opengameart.org/content/dark-ambiance)

* Yd - [Insistent](https://opengameart.org/content/insistent-background-loop)

* AlexTheDj - [Heavy Terror Machine](https://www.newgrounds.com/audio/listen/345935)

# License

This project is published under Zlib license.
