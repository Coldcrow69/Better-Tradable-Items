BETTER TRADABLE ITEMS
=====================
RimWorld mod by Coldcrow
Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=3009963773
Source:   https://github.com/Coldcrow69/Better-Tradable-Items


DESCRIPTION
-----------
Better Tradable Items fixes the items vanilla won't let you sell, and makes a short list
buyable too. It borrows from existing mods that each handle one item (credited below) and
adds a few I wanted tradable myself.

Now sellable (vanilla would not take them):
- Stone and slag chunks. Worth next to nothing, but a ship that buys everything will
  haul them away
- Stone blocks (plus Alpha Memes stone blocks when that mod is loaded; those trade both
  ways afterwards, like vanilla blocks)
- Meals
- Gravcore (Odyssey), mechanoid transponder (Biotech), void sculpture (Anomaly), animus
  stone (Royalty)
- Toxic wastepacks (Biotech), at a token value, so a ship that buys everything (the Better
  Orbital Traders scrapyard) will haul them away

Now buyable as well as sellable:
- Ambrosia
- Healer mech serum
- Fish, psilocap, and thrumbomane (Odyssey)
- Ghoul resurrection serum (Anomaly)

The resurrector mech serum stays vanilla: sellable, never for sale. Buying resurrection
changes the game's rules.

Want something added? Leave a comment on the Workshop page.


WHO ACTUALLY BUYS AND SELLS
---------------------------
Tradeability is only half of it. A trader also has to deal in the item's category, so
flipping the switch doesn't make every ship want every item.
- Stone blocks: bulk goods traders deal in raw resources, so they buy blocks.
- Chunks: a silver per hundred. Only a ship that buys everything will take them (the
  Better Orbital Traders scrapyard). Treat it as junk disposal, not income.
- Wastepacks: same deal, a silver per hundred, scrapyard only. They still have to sit
  within a trade beacon's range to reach an orbital ship.
- Meals: outlander and Empire settlements and the orbital bulk goods ship, both ways. Ships
  and caravans that buy expensive goods take fine and lavish meals too.
- Drugs (ambrosia, healer serum, psilocap, ghoul serum): any drug seller. Outlander and
  Empire caravans and bases, orbital bulk goods, exotic, and pirate ships. Healer serum
  also carries the exotic goods tag, so the exotic ship rolls it through that line as
  well; expect one or two on about a quarter to a third of exotic ships.
- Fish: food traders, as raw meat.
- Thrumbomane: textile sellers. Outlander and Empire settlements carry 20 to 40 on their
  silver budget, the vanilla orbital bulk goods trader 110 to 200, the Better Orbital
  Traders version thousands, like every other textile on that ship. Outlander caravans
  only buy textiles; the neolithic bulk goods caravan sells two kinds on a 200 to 600
  silver budget, so 10 to 30 of it when it comes up.
- Transponder: orbital traders buy expensive items in general. Void sculpture: the exotic
  trader and the Better Orbital Traders void peddler have standing orders.
- Gravcore and animus stone: nothing in vanilla buys them. The gravcore is flagged out of
  the general expensive-items rule and the animus stone is a building, which that rule
  skips. The Better Orbital Traders scrapyard takes both, and Vanilla Gravship Expanded's
  traders take the gravcore.


REQUIREMENTS
------------
- RimWorld 1.6 or 1.7.
- No DLC required. DLC items are patched only when their DLC is active.


INSTALLATION
------------
Steam Workshop: subscribe on the page linked above, then enable the mod in the mod list.
Manual: copy the "Better Tradable Items" folder into RimWorld/Mods and enable it. Load
order does not matter.


COMPATIBILITY
-------------
XML only. Works with anything that doesn't also change tradeability on these items. If
another mod does, whichever loads last wins. Nothing in here can crash the game.

Built-in compatibility:
- Alpha Memes stone blocks.
- Vanilla Gravship Expanded: it makes the gravcore buyable and sells it on the combat
  supplier and exotic trader. With it loaded the gravcore is buyable and sellable both, and
  this mod loads after it so the two agree.


FAQ
---
Q: Can this be added mid-save?
A: Yes.

Q: Can this be removed mid-save?
A: Yes.

Q: Do I need the DLCs to use this mod?
A: No.

Q: Is this mod compatible with another mod?
A: Probably. This is an XML only mod, so the worst behavior that you should get is
   unintended item tradeability. It's not likely to cause any crashes, and as long as
   the other mod doesn't modify tradeability values, it's unlikely there will be any
   conflict.

Q: I have a bug, and I think it's caused by this mod. What do?
A: Post a bug report on the Workshop page.

Q: Does it work on the 1.7 unstable branch?
A: Yes. 1.7 moved RimWorld to Ludeon's own Waylith engine, but the defs this mod patches
   did not change, so 1.6 and 1.7 load the same files.

Q: RimWorld updated, but this mod hasn't yet. What do?
A: Life happens sometimes, but I will do my best to update all of my mods, including
   this one, as quickly as I can.

Q: I want to use your mod or pieces of your mod in mine, is that okay?
A: Yes. See LICENSE.txt (MIT), and credit me in your mod's documentation and on its
   Workshop page.


CREDITS
-------
Mod author: Coldcrow
Contact: find me on Steam and Discord.

The following mods by Steam author Meow were used as reference:
- Tradable Meals
- Tradable Stone Blocks

The artwork in this mod's thumbnail includes assets from RimWorld, developed by Ludeon
Studios. I do not claim ownership or authorship of that art. All rights to distribute
and monetize it are reserved by Ludeon Studios.

The font used in this mod's Workshop description is "Rimworld Font", fan-made content
created by Ludeon forums user Marnador for community use in RimWorld content.


LICENSE
-------
MIT. See LICENSE.txt.


CHANGELOG
---------
2.0
- Requires RimWorld 1.6 or 1.7. Support for 1.4 and 1.5 dropped. 1.7 replaced the game
  engine, not the defs this mod touches, so both versions load the same files.
- Toxic wastepacks (Biotech) get a token market value of 0.01. Vanilla marks them tradeable
  but worth zero, which the game treats as untradeable. Only a ship that buys everything
  takes them, a silver per hundred.
- Vanilla Gravship Expanded compatibility. Both mods set the gravcore's tradeability;
  whichever loaded last used to win, and when this mod won, VGE's gravcore stock line
  logged an error on every combat supplier or exotic arrival. Now with VGE loaded the
  gravcore is buyable and sellable both, and this mod loads after it.
- Everything you can pick up is now at least sellable. Stone and slag chunks (vanilla
  None, worth next to nothing), gravcore (Odyssey), mechanoid transponder (Biotech), void
  sculpture (Anomaly), animus stone (Royalty).
- New buyable items: fish, psilocap, and thrumbomane (Odyssey), ghoul resurrection serum
  (Anomaly). Better Orbital Traders 2.0 stocks thrumbomane by the thousand on its bulk
  goods ship, like its other textiles.
- Resurrector mech serum reverted to vanilla (sellable, not buyable). Buying resurrection
  changes the game's death rules, and 1.x let any drug trader roll one.
- Baby food and subcores dropped from the patch list. They were already tradeable in
  vanilla, so the op never did anything.
- All files moved to Common/, loaded through LoadFolders.xml. DLC patches are gated behind
  PatchOperationFindMod. The Alpha Memes patch now checks for that mod's block def instead
  of its display name, so a retitled mod keeps working.
- Formatting and comments pass across every file. Safe to update mid-save.

1.3 and 1.4
- Updated for 1.6 Odyssey. Detailed notes were not kept for these two.

1.2
- Updated for 1.5 Anomaly.

1.1
- Tradable subcores.

1.0
- Tradable stone blocks.
- Tradable ambrosia.
- Tradable meals.
- Tradable baby food.
- Patch for Alpha Memes stone blocks.
