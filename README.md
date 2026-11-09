# Code Chicken Lib — The Hidden Core for Your Favorite Mods

Code Chicken Lib 9minecraft Mod gives other popular mods the shared code they need to run. It does not add any new blocks, items, or creatures to the game on its own. Instead, it works quietly in the background to handle math, 3D models, and lighting. You only need to add this library when another mod asks for it. Without it, those extra mods will fail to load when you start the game.

Acts as a required base for well-known additions like Ender Storage, Chicken Chunks, Translocators, and Wireless Redstone.

## What this build is

An unofficial rebuild of **TheCBProject**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **GNU Lesser General Public License v2.1**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | NeoForge |
| 26.2 | NeoForge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/code-chicken-lib-9minecraft-mod](https://www.9minecraft.net/code-chicken-lib-9minecraft-mod/)

## Credits

Original work by **TheCBProject**. Port and maintenance by 9Minecraft Studios. Licensed GNU Lesser General Public License v2.1; the upstream licence text ships inside every build.
