# Project Pokémon Events Gallery

### What is this?
The collective effort of the Project Pokémon (and other) communities to preserve as much event Pokémon information as possible.

### How do I use this?
#### • Legality with [PKHeX](https://projectpokemon.org/home/files/file/1-pkhex/) and [SysBot.NET](https://projectpokemon.org/home/files/file/4207-sysbotnet-automatic-build/)
1. Download this repository.
1. Extract the contents to a folder `mgdb` in the same folder as `PKHeX.exe` or `SysBot.exe`.

#### • PKM creation with PKHeX
1. Find the specific wondercard or Pokémon file.
1. Drag/drop the file onto PKHeX in the spot where you want that Pokémon.

#### • In-game Mystery Gift redemption
* For Gen 3 events, use either the [WC3 Plugin](https://projectpokemon.org/home/files/file/4161-pkhex-plugin-wc3-plugin/) or the [Mystery Gift Tool](https://projectpokemon.org/home/forums/topic/39184-gen-iii-mystery-gift-tool-nintendo-events-wondercards-e-trainer-cards-and-e-berry-editor-and-more/)
* For Gen 4, 5, 6 and 7 (3DS) events, use the [PKHeX Mystery Gift feature](https://projectpokemon.org/home/tutorials/save-editing/using-pkhex/importing-wondercards-r29/)
* For Gen 7 (Switch), 8 and 9 events, use the [Switch Gift Data Manager](https://projectpokemon.org/home/forums/topic/62491-switch-gift-data-manager-import-wondercards-into-switch-games-by-faking-bcat-packages/)

#### • Import Raid Events
* For Sword/Shield raids, follow our [PKHeX Block Editing tutorial](https://projectpokemon.org/tutorials/save-editing/gen-8_157/block-editing-r106/). The blocks to be imported are labeled as follows: `*Object KDropRewards`, `*Object KDaiEncount`, `*Object KBonusRewards`, `*Object KNormalEncount`, `*Object KNormalEncountRigel1`, `*Object KNormalEncountRigel2`. 
* For Scarlet/Violet raids, follow the [tutorial for importing Poké Portal News](https://projectpokemon.org/home/tutorials/save-editing/gen-9/gen-9-specific-edits-importing-poké-portal-news-raid-events-r124/).

### How do I get Gen 8 and 9 events if they are not on the save file?
Pokemon games on Nintendo Switch use a system called BCAT. BCAT data is synchronized when your game goes online.
Use [JKSV](https://github.com/J-D-K/JKSV) to export the BCAT files. BCAT includes wondercards, raid events etc.
See the section below on how to contribute your bcat export.

### I don't see _X_ event. Can I contribute it?
Sure, there are several ways.
1. Create an [issue](https://github.com/projectpokemon/EventsGallery/issues/new) and attach the event
1. Create a [pull request](https://github.com/projectpokemon/EventsGallery/compare)
1. Make a [contribution post](https://projectpokemon.org/home/forums/forum/64-event-contributions/) on our forums

### What is a post event redemption?
These are events that were redeemed using the original hardware (such as PCNY Gotta Catch 'Em All) after the original event period.
Not all events will be categorized like this due to various reasons. Please open an [issue](https://github.com/projectpokemon/EventsGallery/issues/new) for questions.

### It looks like some Gen 4 events are hacks, what's up with that?
Unfortunately some of the Gen 4 wondercards are missing but we have the mystery gifts (PGT).
To keep everything consistent, the PGTs were converted to wondercards with placeholder data.
There is a list of missing wondercards [here](https://rebrand.ly/missib7ab).
Do you have one of these events? Please contribute it!

### Where are the Gen 4 PCD files?
To keep the format consistent, all PCDs were converted to WC4 format.
The data is the same except the Pokémon template itself is decoded, just like PK4 files.

#### • Converting WC4 back to PCD
1. Import/Export with PKHex
2. Use the [PCDWC4 Converter](https://github.com/projectpokemon/PCDWC4Converter/releases/latest)

### Where are your individual Pokémon files for Gen 4+?
Posting the individual Pokémon not only contributes to cloning, but does not help our legality research efforts.
The exception are GTS traded Pokémon from Daisuki, of which many are missing or incorrect in the gallery.
