# Minetest Mod Storage Drawers


**************  THIS BRANCH IS STILL IN RE-WRITE MODE **************

it is not yet production ready, you may mess up your world if you use this
mod in a world that already has drawers in it.

*********************** YOU HAVE BEEN WARNED ***********************

[[If you are aware of this and want to contribute](doc/contribute.md)]




the links bellow this line point to upstream, use the link above for now.


[![ContentDB](https://content.minetest.net/packages/LNJ/drawers/shields/downloads/)](https://content.minetest.net/packages/LNJ/drawers/)
![](https://github.com/minetest-mods/drawers/workflows/luacheck/badge.svg)

Version 0.6.1, License: MIT

## Description
This mod adds simple item storages showing the item's inventory image in the
front. By left- or right-clicking the image you can take or add stacks. If you
also hold the sneak-key only a single item will be removed/added.

There's also a 'Drawer Controller' which can insert items automatically into a
network of drawer cabinets. Just place the cabinets next to each other, so they
are connected and the drawer controller will sort the items automatically. The
'Drawer Trim' can be used to connect cabinets and controller too.

Do you have too many cobblestones for one cabinet? No problem, just add some
upgrades to your cabinet! They are available in different sizes and are
crafted from steel, gold, obsidian, diamonds or mithril.

## Notes
TODO: test current dependencies
This mod requires Minetest 0.4.14 or later. The `default` mod from MTG or the
MineClone 2 mods are only optional dependencies for crafting recipes.

## To-Do
- [x] Add usable 1x1 1-drawer cabinet
- [x] Add a drawer controller for auto-sorting items into a drawer-network
- [ ] Add half-sized cabinets
- [x] Add 2x2 and 1x2, 4 and 2 drawer cabinets.
- [ ] Add compacting drawers for auto-crafting blocks/ingots/fragments
- [x] Add a key (or something similar) for locking the item (so the item is
      also displayed at count 0)
      Special-key + right-click to lock,
      Special-key + left-click to un-lock.
- [ ] Add duct tape to transport drawers
- [x] Support pipeworks
- [ ] Support hoppers (needs hoppers mod change)
- [x] Make drawers upgradable
- [x] Add drawers in all wood types
- [x] Make them digilines compatible

## Bug reports and suggestions
You can report bugs and suggest ideas on [GitHub](http://github.com/lnj2/drawers/issues/new),
alternatively you can also [email](mailto:git@lnj.li) me.

## Credits
#### Thanks to:
* Justin Aquadro ([@jaquadro](http://github.com/jaquadro)), developer of the
	original Minecraft Mod (also licensed under MIT :smiley:) — Textures and Ideas
* Mango Tango <<mtango688@gmail.com>> ([@mtango688](http://github.com/mtango688)),
	creator of the Minetest Mod ["Caches"](https://github.com/mtango688/caches/)
	— I reused some code by you. :)

## Links
* [Minetest Forums](https://forum.minetest.net/viewtopic.php?f=9&t=17134)
* [Minetest Wiki](http://wiki.minetest.net/Mods/Storage_Drawers)
* [Weblate](https://hosted.weblate.org/projects/minetest/mod-storage-drawers/)
* [GitHub](http://github.com/minetest-mods/drawers/)

