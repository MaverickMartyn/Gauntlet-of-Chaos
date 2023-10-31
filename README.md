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

## Looking for a Download?
[![Download button]({{ site.baseurl }}/assets/downloadbutton.png 'Download modpack')]({{ site.github.releases_url }}){:target="_blank"}

## Relevant links
* For an overview of the included mods, check out the [Mod list](MODS.md)
* Follow current progress on the [TODO list](TODO.md)
* Download the pack [here]({{ site.github.releases_url }})
* Find code [here]({{ site.github.repository_url }})

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

## Building the modpack
### Requirements
* [Packwiz](https://packwiz.infra.link/){:target="_blank"} for managing the included mods and files.
* [Git LFS](https://git-lfs.com/){:target="_blank"} for handling larger files like internal .jar mod files.

### How to build
* After adding or updating internal files like configs, run `packwiz refresh` to update the index. The index should be updated and committed after each change on the `master` branch.
* Run `packwiz serve` to host a local webserver, serving the mod files for local testing.

## Building the webpage locally
### Requirements
* [Jekyll](https://jekyllrb.com/docs/){:target="_blank"} for building GitHub pages site locally.

### How to build
* Run `bundle exec jekyll serve` to serve the Ruby site locally.

## Releasing updates
The `.github/workflows/static.yml` file defines a GitHub Actions workflow, which builds the site and hosts it along with all mod files on GitHub Pages.  
This workflow is configured to automatically publish on new commits to the `master` branch.
