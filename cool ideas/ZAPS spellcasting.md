# Mod idea for spellcasting
### Basic idea
This mod would add a Noita styled spellcasting system.

It would introduce wands and spells. 
## Wands
### Wand Basics
The wands would have the following different types of stats, reminiscent of Noita's wands:
- Mana Capacity
- Mana Recharge Speed (in mana generated per sec)
- Spell Capacity
- Time Between Casts (in sec)
- Reload Time (in sec)
- Spread (in +degrees)
- Always Cast

Wands can be used by right clicking, which will fire off whatever spells are in the wand from left to right based on the "Time Between Casts" stat. After that, it will 'reload', taking whatever amount of time the "Reload Time" stat says.
You can modify the spells in a wand by interacting with a new workstation called the "Tinkering Station". It will open up a menu when you insert your wand in it, allowing you to put spells in the slots or take spells out.
Wands will have durability that is consumed when casting a spell. A wand can be repaired in an Anvil or a Tinkering Station (repairing it in a station will not cost EXP but cost more material).
The player will start with a "Stick Wand" with a "Lesser Spell Bolt" on it when they first join a world {Configurable}.
## Spells
### Spell Basics
Spells are broken up into different categories, those being:
- Projectile
- Static
- Modifier

Projectile spells can have the following stats:
- Damage (in specified damage type)
   - Damage would have different damage types, such as Magic, Projectile, Explosive, Burn, Freeze, Healing, etc.
- Mana Cost (in mana)
- Additional Time Between Casts (in +sec)
- Additional Reload Time (in +sec)
- Spread (in degrees)
- Uses
- Additional Effects

Static spells can have the following stats:
- Damage (in specified damage type)
- Mana Cost
- Additional Time Between Casts (in +sec)
- Additional Reload Time (in +sec)
- Instantaneous or Over Time
- Uses
- Additional Effects

Modifier spells can have the following stats:
- Modify *x* Stat (+,-,×,÷)
- Mana Cost
- Uses
- Additional Effects (preferably ones that modify the base spell)

Spells will usually be obtained through loot chests, rare mob drops, or villager trades.
When a spell runs out of uses, it can be repaired with any `#forge:gems` at a Tinkering Station.
Certain spells can be combined together at a Tinkering Station to form greater spells.
Modifier spells' Mana Cost is only applied to the spell it is modifying.
### All Spells
These are all my ideas for the spells that would be added.

**Lesser Spell Bolt**
- *A small bolt that does petty damage, cheap to cast.*
- Projectile
- Stats:
   - 1 Projectile Damage, 1 Magic Damage
   - 10 Mana Cost
   - +0.1sec Additional TBC
   - +0.2sec Additional RT
   - 5° Spread
   - Is affected by gravity
- Shoots a small, purple projectile that leaves behind a wake of purple particles. Can be found in most loot chests.

**Spell Bolt**
- *A larger form of the redundant lesser spell bolt.*
- Projectile
- Stats:
   - 3 Projectile Damage, 1 Magic Damage
   - 15 Mana Cost
   - +0.15sec Additional TBC
   - +0.30sec Additional RT
   - 3° Spread
   - Is affected by gravity
- Just a larger form of the lesser bolt. Made by combining two of the lesser bolts.

**Damage Imbue**
- *A spell that seemingly adds damage to other spells.*
- Modifier
- Stats:
   - +2 Projectile Damage
   - 15 Mana Cost
- Obtained as a rare drop from most undead.

**Dual Cast**
- *A spell that enables you to fire off two spells at once.*
- Modifier
- Stats:
   - 5 Mana Cost
- Found as a sort of rare spell in village chests. Enables the caster to fire two Projectile/Static spells at once.
   - Any modifiers applied to the Dual Cast will be applied to the spells within the Dual Cast.
   - The Spread of both spells will be combined.

**Add Mana**
- *This spell seemingly reduces the cost of the spell it is applied to.*
- Modifier
- Stats:
   - -20 Mana Cost
   - +0.2 Additional RT
- Found in dungeon chests.
