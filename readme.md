# About
  There is a **ton** of loot to haul around and a ton to organize. You want to hit that *Move All* button, but it ends up stashing those few things you wanted to keep in your pockets. You *could* Favorite them, after all, that way they don't get moved and you get easy access to them. But what about the items you *don't* need easy access to, but *do* want to keep on you at all times? Your Quick Action Wheel items, your Quick Use slots, items that you don't use directly but used for something else (batteries, matches, bolts, **AMMOS**, etc.), on and on and on; you have too much you want to always keep, and you can only Favorite so many before you just start losing your favorites among your "less-than-favorites-but-still-favorites."
  
  We need a way to manage these not-quite-favorites, to block certain items from being moved on the *Move All* action. *G_FLAT* submitted their solution **Move All Blocker Extended**, which introduced some wonderful functionality, such as blocking favorites from QRS and blocking unusable parts (per their other mod) and junk items from being moved into player stashes. But I wanted a dynamic option, because there were just too many things I wanted blocked. So, building off their mod (thank you *G_FLAT* for your work, all credits down below) I made **Move All Blocker Super Extended** for all our hoarding needs!
  
  **tl;dr: Dynamically block certain items from the *Move All* button. And, block those items from QRS (Quick Release Stash). And a bit more.**
  
# Features
- Dynamically block/unblock items from the *Move All* button with a right-click-menu option
- Block items from the QRS (quick release stash) action
- Automatically block all ammos for your equipped weapons
- Hide/show the right-click menu option on the fly, so you only see it when you want it. Don't clutter up that context menu
- A config file to block items across all your characters and saves, for those things you always want blocked from now to the end of time
- Edit and refresh the config file **while in-game**
- An MCM menu to configure just about everything
- And, if things get out of hand, an option to clear your list of blocked items, to start fresh once more.
- Built-in compatibility with *Haruka*'s **Auto Favorite Ammos** mod

# How To Use
## To Block an Item:
  1. Hover over the item you wish to block.
  2. select `Blacklist from Move-All`
  3. Profit!!!
## Temporarily Show/Hide Block Option
  1. Open inventory
  2. Make sure no menus are open, no right-click menus
  3. Hold your `Modifier` key, defaults to `Left-Control` (change in MCM)
  4. Right Click item
  5. Block it
## Toggle Show/Hide Block Option
  1. Make sure no right-click menus are open, you're just in the inventory screen
  2. Hold your `Modifier` key, and keep holding it
  3. **Now**, press the `Toggle Keybind`, defaults to `R` (change in MCM)
  4. Right click an item
  5. See that the menu is/isn't there!!
## Use the Config File
  1. Find the section name of the item you wish to block. 
    - if you don't know it, it's usually found in a file inside `gamedata/configs/items/items/`
  2. Open the config file `gamedata/configs/items/settings/ym_move_all_blocked_items.ltx`
    - The config file comes with some defaults I thought you might find useful. Delete them if you wish
  3. Under the `[ym_blocked_items]` section, add your section name
  4. Save the file
  5. Go into the MCM
  6. Make sure `Enable Config File` is checked
  7. Press the `Refresh Config File` checkbox
  8. Save and exit
  9. Your item should be blocked now

# Installation
  1. If you have *G_FLAT*'s **Move All Blocker Extended** mod, disable it
  2. Install this mod
  3. Put anywhere you want in your load order
  4. Optionally, move the `ym_move_all_blocked_items.ltx` config file to its own separate mod in MO2. This ensures if you reinstall the mod, or update it, your config file survives through it all. Find it in `gamedata/configs/items/settings/ym_move_all_blocked_items.ltx` inside this mod.
# Compatibility
  - Not compatible with *G_FLAT*'s **Move All Blocker Extended** mod. This mod directly overwrites everything from that mod.
  - Other mods that handle keeping favorites on QRS or something like that:
    - compatible, but this mod already includes that functionality
  - Haruka's **Auto Favorite Ammos** mod:
    - Patch built-in. Enable/disable in MCM
  - If you find something else, let me know! Report bugs!
# Source
  Find the source code here:
  https://github.com/Y3sMan/Move-All-Blocker-Super-Extended
# Credits
- *G_FLAT*'s for their awesome **Move All Blocker Extended**. Without it, I wouldn't have thought of this. If you see this and want more credit, or want me to completely remove your files, just let me know! I'm more than happy to accomodate.
- Grok, for GAMMA
- The Anomaly developers for their work and dedication
- You guys, the fans of STALKER, who keep this community thriving