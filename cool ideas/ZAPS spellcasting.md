# Mod idea for spellcasting
## Let's call it "Zap's Spellcasting"
### Basic idea:
This mod would add a Noita styled spellcasting system.

It would introduce wands and spells. 

### Wand Basics
The wands would have the following different types of stats, reminiscent of Noita's wands:
- Mana Capacity
- Mana Recharge Speed (in mana generated per sec)
- Spell Capacity
- Time Between Casts (in sec)
- Reload Time (in sec)
- Spread (in +degrees)
- {Optional} Always Cast

Wands can be used by right clicking, which will fire off whatever spells are in the wand from left to right based on the "Time Between Casts" stat. After that, it will 'reload', taking whatever amount of time the "Reload Time" stat says.
You can modify the spells in a wand by interacting with a new workstation called the "Tinkering Station". It will open up a menu when you insert your wand in it, allowing you to put spells in the slots or take spells out.
Wands will have durability that is consumed when casting a spell. A wand can be repaired in an Anvil or a Tinkering Station (repairing it in a station will not cost EXP but cost more material).
The player will start with a "Stick Wand" with a "Little Spell Bolt" on it when they first join a world {Optional}.
### Spell Basics
Spells are broken up into different categories, those being:
- Projectile
- Static
- Modifier

Projectile spells can have the following stats:
- Damage (in specified damage type)
   - Damage would have different damage types, such as Magic, Projectile, Explosive, Burn, Freeze, etc.
- Mana Cost (in mana)
- Additional Time Between Casts (in +sec)
- Additional Reload Time (in +sec)
- Spread (in degrees)
- {Optional} Uses
- Additional Effects

Static spells can have the following stats:
- Damage (in specified damage type)
- Mana Cost
- Additional Time Between Casts (in +sec)
- Additional Reload Time (in +sec)
- Instantaneous or Over Time
- {Optional} Uses
- Additional Effects

Modifier spells can have the following stats:
- Modify *x* Stat (+,-,×,÷)
- Mana Cost
- {Optional} Uses
- Additional Effects (preferably ones that modify the base spell)

Spells will usually be obtained through loot chests, rare mob drops, or villager trades.
When a spell runs out of uses, it can be repaired with any `#forge:gems` at a Tinkering Station.
Certain spells can be combined together at a Tinkering Station to form greater spells.
