---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: The Gauntlet of Chaos
permalink: /
---

# The Gauntlet of Chaos
> This pack is focused on surviving the harsh environment in a modded hardcore scenario.  
There are multiple dangers in the form of natural disasters, new mobs, dungeons and bosses.  
In multiplayer, players can be rescued within a time limit if downed. Upon death, a corpse is left behind. Extra lives can be earned through progress.  
Follow the Quest Book (with completely custom built quests), and take on the *Gauntlet of Chaos*, as you beat each boss in the pack to restore order to the world.  
Includes some light magic and tech mods, as well as custom ship building for travel.

**Note: Still designing. Everything is subject to change.**

## More info
* [Mod list](MODS.md)
* [TODO list](TODO.md)
* [Download the pack here](https://github.com/MaverickMartyn/Gauntlet-of-Chaos/releases/)
* [Repository](https://github.com/MaverickMartyn/Gauntlet-of-Chaos/)
* [Pack format specification](https://github.com/packwiz/packwiz-spec)

## Tweaked Settings
* **Controls and Keybinds**
    * Many rebinds. See [options.txt](options.txt) for details.
* **Physics Mod**
    * Disabled `collapse` setting, to avoid the aggressive structural integrity implementation.
    * Maxed out `stiffness` at `5000`, and set `collision` to `false` on all trapdoors, to fix their weird behavior.
* **Better Animations Collection**
    * Disabled Wobbly Creepers since they looks a bit silly.
* **Inventory Profiles**
    * Disabled Continous Crafting. It's a little confusing if enabled by default.
* **Hardcore Questing Mode**
    * Added custom logo on frontpage. (Might want to replace with more appropriate art at some point)
    * Custom quest lines and rewards.
* **Vanilla**
    * Set GUI scale to 2 (Better default size).
    * Set music volume to 10% by default.
    * Swapped sprint and sneak controls.
    * Disabled auto jumping.
    * Skipped multiplayer warning.
    * Added servers to server list.
* **Shaders and Resource Packs**
    * *Complementary Unbound* shaders enabled by default.
    * *Weather2 Retextured* enabled by default.
* **Weather2**
    * Disabled tornados and cyclones for now.  
    Need to make sure it isn't too destructive.
* **Lucky Block**
    * Disabled "Luck Crafting".
    * Disabled crafting of Lucky Blocks using Craft Tweaker.
    * Disabled natural generation