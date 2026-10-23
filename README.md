# Better Tradable Items

RimWorld mod by Coldcrow. Everything you can pick up becomes sellable, and a short list becomes buyable too.

Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=3009963773

## Now sellable

Vanilla would not take these at all.

- Stone and slag chunks. Worth next to nothing, but a ship that buys everything will haul them away
- Stone blocks (plus Alpha Memes stone blocks when that mod is loaded; those trade both ways afterwards, like vanilla blocks)
- Meals
- Gravcore (Odyssey), mechanoid transponder (Biotech), void sculpture (Anomaly), animus stone (Royalty)
- Toxic wastepacks (Biotech), at a token value, so a ship that buys everything (the Better Orbital Traders scrapyard) will haul them away

## Now buyable as well

- Ambrosia
- Healer mech serum
- Fish, psilocap, and thrumbomane (Odyssey)
- Ghoul resurrection serum (Anomaly)

The resurrector mech serum stays vanilla: sellable, never for sale. Buying resurrection changes the game's rules.

Tradeability is only half of trading; a trader also has to deal in the item's category. Blocks go to bulk goods traders, meals to anyone carrying food, drugs to any drug seller, chunks only to a ship that buys everything. Want something added? Leave a comment on the Workshop page.

## Requirements

- RimWorld 1.6 or 1.7
- No DLC required. DLC items are patched only when their DLC is active

## Compatibility

XML only. Safe to add or remove mid-save. Conflicts only with mods that also change tradeability on the same items, and then whichever loads last wins. Built in: Alpha Memes stone blocks, and Vanilla Gravship Expanded (with it loaded the gravcore is buyable and sellable both, and this mod loads after it).

## Install

Subscribe on the Workshop, or copy the `Better Tradable Items` folder into `RimWorld/Mods`. Load order does not matter.

## Repo layout

```
Better Tradable Items/
  About/            mod metadata, preview image, workshop id
  Common/Patches/   Core, Royalty, Biotech, Anomaly, Odyssey, and Alpha Memes patches, all gated
  LoadFolders.xml   points 1.6 and 1.7 at Common/
  ReadMe.txt        full notes, FAQ, changelog (ships with the mod)
  LICENSE.txt
```

## Better series

- [Better Kibble](https://github.com/Coldcrow69/Better-Kibble)
- [Better Nutrifungus](https://github.com/Coldcrow69/Better-Nutrifungus)
- [Better Orbital Traders](https://github.com/Coldcrow69/Better-Orbital-Traders)

## License

MIT. See [LICENSE](LICENSE).
