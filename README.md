# Project Pokémon Events Gallery

### What is this?
The collective effort of the Project Pokémon (and other) communities to preserve as much event Pokémon information as possible.

### How do I use this?
#### • Legality with [PKHeX](https://projectpokemon.org/home/files/file/1-pkhex/)
1. Download this repository.
1. Extract the contents to a folder `mgdb` in the same folder as `PKHeX.exe`.

#### • Injection with PKHeX
1. Find the specific wondercard or Pokémon file.
1. Drag/drop the file onto PKHeX in the spot where you want that Pokémon.

### How do I get Gen 8 Wondercards if they are not on the save file?
Pokemon LGPE and Sword/Shield use a system called BCAT. BCAT data is synchronized when your game goes online.
Use [JKSV](https://github.com/J-D-K/JKSV) to export the BCAT files. BCAT includes wondercards, wild area news, tournament rules, etc.
See the section below on how to contribute your bcat export.

### What is a post event redemption?
These are events that were redeemed using the original hardware (such as PCNY Gotta Catch 'Em All) after the original event period.
Not all events will be categorized like this due to various reasons. Please open an [issue](https://github.com/projectpokemon/EventsGallery/issues/new) for questions.

### I don't see _X_ event. Can I contribute it?
Sure, there are several ways.
1. Create an [issue](https://github.com/projectpokemon/EventsGallery/issues/new) and attach the event
1. Create a [pull request](https://github.com/projectpokemon/EventsGallery/compare)
1. Make a [contribution post](https://projectpokemon.org/home/forums/forum/64-event-contributions/) on our forums

### It looks like some Gen 4 events are hacks, what's up with that?
Unfortunately some of the Gen 4 wondercards are missing but we have the mystery gifts (PGT).
To keep everything consistent, the PGTs were converted to wondercards with placeholder data.
There is a list of missing wondercards [here](https://rebrand.ly/missib7ab).
Do you have one of these events? Please contribute it!

### Where are the Gen 4 PCD files?
To keep the format consistent, all PCDs were converted to WC4 format.
The data is the same except the Pokémon template itself is decoded, just like PK4 files.

### Where are your individual Pokémon files for Gen 4+?
Posting the individual Pokémon not only contributes to cloning, but does not help our legality research efforts.
The exception are GTS traded Pokémon from Daisuki, of which many are missing or incorrect in the gallery.
