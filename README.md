# MiSTer-gameboy-palettes

A collection of community palettes for GBC and SGB for use with the MiSTer Gameboy
core.

**Note**: this is a mirror of the palette collection initially maintained by R.A.Helllford
for the Analogue Pocket.

You can find the original archive
[served from discord here](https://cdn.discordapp.com/attachments/136631046933315585/1188860302167650417/AP_-_Palettes_Collection_-_2023-12-25_v3.zip?ex=659c0f6f&is=65899a6f&hm=91fc646ff66b817e6d22adb0e9568cbdc5f560eae0044d0b20c1131c0930eaf4&),
and [an alternate archive mirror here](https://files.catbox.moe/4bujqi.zip)
and the currently maintained Analogue Pocket version [on Github here](https://github.com/davewongillies/openfpga-palettes).

More information and discussion can be found on [r/AnaloguePocket](https://www.reddit.com/r/AnaloguePocket/comments/18q2iz1/collection_of_all_official_game_boy_color_and)

## Installation

1. Add the following to `/media/fat/downloader.ini`

```ini
[gameboy_palettes]
db_url = https://raw.githubusercontent.com/davewongillies/MiSTer-gameboy-palettes/db/db.json.zip
```

2. Run `update_all` or `update` from the Scripts menu on your MiSTer

## Palettes

Full List of palettes:

* Game Boy Color: All 12 combo palettes, all 45 unique Game palettes, all 6
  unused palettes
* Virtual Consoles: Grey and Green palettes from both the 3DS and Nintendo Switch
  Online apps
* All 32 Super Game Boy 2: Vaporwave Edition palettes
* Trashuncles Mister palettes, all 21 of them
* All 7 Sameboy palettes
* A bunch of BGB palettes
* 16 Limited Edition palettes to complement the Classic series, transparent
  series, and the Glow In The Dark edition
* 4 Pipboy styles to pick from (Amber, Green, Blue, and White) plus "inverted"
  ones for the hell of it
* 300 palettes covering a ton of systems and themes by @TheWolfBunny64
  * Pokemon Mini + Virtual Boy
  * Game & Watch Classic LCD
  * Other gaming displays: Dreamcast VMU, Gamate + MegaDuck, Game Master,
    Game.com, Gamebuino Classic, GameKing, Microvision, Neo Geo Pocket,
    PocketStation, Supervision
  * Misc Displays: Nokia 3310, Texas Instruments

## Credits

* u/Al\_Levin: For the unique Games and unused palettes from the GBC Bios
* @TheRealFlamepanther: For the SGB2: Vaporwave Edition palettes
* TheWolfBunny64 on DeviantArt: NSO and 3DS palettes, as well as all the other
  displays listed above
* Sho on Discord for the BGB palettes
* @MonOfLetters for porting the stock Analogue Pocket palettes
* u/RAHelllord: for the LE and Pipboy palettes with the power eye dropper tools,
  converting the rest from their respective creators, and kicking off this whole
  collection in the first place
