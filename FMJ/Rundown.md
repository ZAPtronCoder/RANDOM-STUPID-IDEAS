# What is FMJ?
## The Concept
### Rudimentary Rundown
FMJ (or in better terms, Full Metal Jacket) was originally going to be a fork of popular mod CGM (Mr. Crayfish's Gun Mod), we (being me and squoshi) decided that we would instead start from the ground up -- code from scratch. The mod would have Unturned-styled gunplay and gun customization with all sorts of little special things like encouraging blast jumping, more bullet variants and extended mags, compat with other mods, and whatever I can think of; after all, it's just a concept.

### Libraries?
Our plan is to use three library mods to make this whole ordeal work, those mods being:
- Lodestone
    - This will provide us with tools for VFX-related things.
- CoFH Core
    - This will provide us with already existing particles to toy with, textures that dynamically change with stack size, and other misc stuff like the Holding enchantment.
- playerAnimator
    - This will provide us with tools for making things like gun animations (reload, idle, firing).

## How Will it Work?
### Bullets and Magazines
Bullets will be split into 7 types, those being: *Pistol Cartridges*, *Rifle Cartridges*, *High-Caliber Cartridges*, *Thin Shells*, *Shells*, *Grenade Shells*, and *Rockets*. Pistol Cartridges and Thin Shells will be the starting ammo types for the mod. Ammo types have several variants, I've covered those in the "Random Item Ideas" file.

Magazines on the other hand will hold these ammo types. Of course there won't be magazines for things like Grenade Shells and Rockets. There will be several different types of magazines, some having extended and smaller variants and hold all sorts of ammo. Magazines will be able to be loaded via crafting them with the ammo it can hold, or loading bullets into it like a bundle.

Some guns don't use magazines, and either have internal mags/tubes or are breach-loaded. These will be loaded with ammo directly instead of by use of a magazine.

### Guns
Guns includes everything from revolvers to rocket launchers in this mod. Guns can be fired by pressing <kbd>Mouse 1</kbd> and can be aimed with by pressing <kbd>Mouse 2</kbd>. 

Reloading a gun is as simple as pressing <kbd>R</kbd> while holding it, which will take ammo/mags from either your offhand, the closest slot to your gun in the hotbar, or from top-left to the bottom-right of your inventory. Alternatively, you can treat the gun like a bundle when loading and taking out ammo/mags.

When pressing <kbd>T</kbd> while holding a gun, it will open the in-world GUI for the gun, allowing you to better customize your gun and extract ammo/mags via the menu instead of previously mentioned methods. Most guns will have slots for you to put a sight and a slot for you to put the ammo/mag. Others may have a barrel, underbarrel, side, and stock. Using <kbd>Mouse 1</kbd> on any of these slots will show all respective items in your inventory that can go in that slot in a row next to the slot; using <kbd>Mouse 1</kbd> on any item in that row will equip it into that slot, if you were to instead click on a already equipped item after clicking on the slot, it will unequip it from the gun.

