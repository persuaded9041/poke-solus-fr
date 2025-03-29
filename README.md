# Pokémon Solus RGB

<p align="center" style="margin-left: 10%; margin-right: 10%">
<img src="screenshots/box-front-solus-triple.png">
</p>

_Pokémon Solus RGB_ is a minimal, near-vanilla, faithful romhack of Pokémon Red/Blue for Game Boy, with a focus on an enhanced **solo gameplay experience**. It is based on the [disassembly of Pokémon Red and Blue][pokered].

For a detailed look at all the changes in this romhack, read the [Feature Log][featurelog]. For a video overview, watch the [trailer][trailer]. Join the [Solus Discord][solusdiscord] to offer any feedback.

Just want the patch? Download [here][releases].

Don't know where to start? Read the [beginner setup guide][howtoplay].

## Table of Contents
- [Elevator pitch](#elevator-pitch)
- [Versions](#versions)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Links](#links)
- [Credits](#credits)
- [Support the project](#support-the-solus-project)

## Elevator pitch

_Pokémon Solus RGB_ is a near-vanilla romhack of Gen 1 (Red & Blue). It changes _only a few things_ from the original games, without overhauling so much that it ceases to be Gen 1, and the whole thing becomes a [Ship of Theseus paradox](https://en.wikipedia.org/wiki/Ship_of_Theseus).

Quick overview of changes:
1. All 151 Pokémon are obtainable through normal means
2. Some new gameplay features have been added
    - HMs can be taught to party Pokémon without using up one of their move slots
    - Four new TMs have been added to support forward-patched learnsets
    - Trades can be performed in-game via the Trader NPC
    - Battle HUD additions: EXP bar and 'already caught' indicator
    - Professor Oak can be battled after beating the Pokémon League
3. Pokémon learnsets have been partially forward-patched via Yellow Version and Gen 2 tradeback learnsets
4. Some visual content is changed (sprites)
5. Some bugs/oversights from vanilla are fixed
    - Ghost-type is now super effective against Psychic-type
    - Focus Energy no longer quarters critical hit chance
    - A couple other things

For a detailed look at all the changes, check out the [Feature Log][featurelog].

## Versions

There are three versions of this romhack: _Solus Red_, _Solus Green_, and _Solus Blue_. The differences between versions are solely cosmetic (palettes, title screen text, etc.), as this project consolidates any of the meaningful version-specific differences that existed across versions, such as Pokémon availability. For a complete list of version differences, check [here][versiondifferences].

_Note_: _Solus Green_, if played on Game Boy Color, uses the GBC's built-in green "duochrome" palette. This is the same one which was used by the Japanese release of Pokémon Green Version.

## Installation

### Patching a vanilla ROM

To patch a vanilla Pokémon Red/Blue Version ROM, download a `.bps` patch file from the [releases page][releases], and then apply it to your ROM using [this online patcher](https://www.marcrobledo.com/RomPatcher.js/) or your patcher of choice.
- For _Solus Red_ or _Solus Green_, patch a vanilla Red Version ROM
- For _Solus Blue_, patch a vanilla Blue Version ROM

### Building all three ROMs from source

If you're new to the [`pokered`][pokered] disassembly, learn how to install prerequisites and build the ROMs in the [install guide][installation].

Otherwise, if your environment for building the vanilla ROMs is already set up, the procedure here is the same. Just clone this repository, `cd` into it, and run `make`.

### Modifying this romhack
If you want to make some tweaks to this romhack before building the ROMs, or if you want to use this romhack as a starting point for your own, read [this document][howtomod] that I've written.

## Screenshots
<details>
    <summary><i>Click to show/hide screenshots</i></summary>

![solusredtitle](./screenshots/solus-red-gbc-title.png)
![solusgreentitle](./screenshots/solus-green-gbc-title.png)
![solusbluetitle](./screenshots/solus-blue-gbc-title.png)
![battlehud](./screenshots/battle_hud.png)
![traderhouse](./screenshots/trader_house.png)
![trader](./screenshots/trader.png)
![trader2](./screenshots/trader_2.png)
![trader3](./screenshots/trader_3.png)
![fossilroomladder](./screenshots/fossil_room_ladder.png)
![fossilroom](./screenshots/fossil_room.png)
![tmclerk](./screenshots/tm_clerk.png)
![tmclerkpunches](./screenshots/tm_clerk_punches.png)
![tmclerk3](./screenshots/tm_clerk_3.png)
![tm51](./screenshots/tm_flamethrower.png)
![tm52](./screenshots/tm_fire_punch.png)
![tm53](./screenshots/tm_ice_punch.png)
![tm54](./screenshots/tm_thunderpunch.png)
![mewroom](./screenshots/mew_room.png)
![mew](./screenshots/mew.png)
![mew2](./screenshots/mew_2.png)
![mew3](./screenshots/mew_3.png)
![fieldmove](./screenshots/field_move.png)
![fieldmove2](./screenshots/field_move_2.png)
![porygonsalesman](./screenshots/porygon_salesman.png)
![porygonsalesman2](./screenshots/porygon_salesman_2.png)
![porygonsalesman3](./screenshots/porygon_salesman_3.png)
![porygonsalesman6](./screenshots/porygon_salesman_6.png)
![billsfather](./screenshots/bills_father.png)
![billsfather2](./screenshots/bills_father_2.png)
![billsfather3](./screenshots/bills_father_3.png)
![oakbattle](./screenshots/oak_battle.png)
</details>

## Links

### Solus RGB
- [Solus RGB wiki][soluswiki]
- [Feature Log][featurelog] (comprehensive list of all changes from vanilla)
- [Changelog][changelog] (overview of the changes introduced in each release)
- [Planned features][planned]
- [Testimonials][testimonials]
- [RomhackPlaza page][romhackplaza]
- [Box art and cartridge labels][physical]
- [Original (crude) design document][designdoc]

### Published media
- [Blog post][blogpost]
- [Blog post 2][blogpost2]
- [Solus video playlist][solusplaylist]

### PRET
- [pokered disassembly][pokered] (from which this romhack is forked)
- [pokered wiki][wiki] (many helpful tutorials)
- [PRET Discord server][pretdiscord]

### Other relevant works
- [Shin Pokémon romhack][shinpokered] (credit for the Field Move slot implementation)
- [pokeworld][pokeworld] (a very helpful tool for visualizing the Kanto overworld)
- [Polished Map][polishedmap] (map/tileset editor)
- [French translation of Solus][poke-solus-fr] by [persuaded9041][persuaded9041]


## Credits
Thank you to [PRET][pret], the entire [PRET Discord server][pretdiscord], and these individuals who were very helpful throughout my work on this project:
- [jojobear13][jojobear13], for the Field Move slot implementation
- [Vortiene][Vortyne], for assistance with assembly and `pokered`
- [unlink2][unlink2], for assistance with Makefile functionality
- [Quadrixis][quadrixis], for collaboration on theorycrafting and general support
- [persuaded9041][persuaded9041], for French translation ([here][poke-solus-fr])
- [Jade Lune][jade] (Discord: _criminalelements_), for Solus artwork (box, cartridge label)

## Support the Solus Project
If you want to show your support, you could:
- Give this repository a Star :star:
- [Join the Solus Discord][solusdiscord] to offer any feedback
- Publish a video review or [leave a written review][romhackplaza]
- Stream or record a playthrough on Twitch or YouTube
- Share the project with someone who might be interested

Any form of support is greatly appreciated.  

Please don't sell this romhack.  
[pokemonsolus.com][homepage] :globe_with_meridians:


[homepage]: https://www.pokemonsolus.com
[pokered]: https://github.com/pret/pokered
[pret]: https://github.com/pret
[wiki]: https://github.com/pret/pokered/wiki
[pretdiscord]: https://discord.gg/d5dubZ3
[shinpokered]: https://github.com/jojobear13/shinpokered
[designdoc]: docs/DESIGN.md
[featurelog]: docs/FEATURES.md
[versiondifferences]: docs/FEATURES.md#version-differences
[installation]: docs/INSTALL.md
[howtomod]: docs/HOW-TO-MOD.md
[changelog]: docs/CHANGELOG.md
[planned]: docs/PLANNED.md
[releases]: https://github.com/Dechrissen/poke-solus-rgb/releases
[pokeworld]: https://www.extratricky.com/pokeworld/rb/1
[polishedmap]: https://github.com/Rangi42/polished-map
[blogpost]: https://derekandersen.net/blog/pokemon-solus-rgb
[blogpost2]: https://derekandersen.net/blog/pokemon-solus-in-retrospect
[romhackplaza]: https://romhackplaza.org/romhacks/pokemon-solus-rgb-game-boy/
[solusplaylist]: https://www.youtube.com/playlist?list=PL-k9sS5iGL6s5MF3GIJqLIPA4662JPsxz
[trailer]: https://www.youtube.com/watch?v=SMto-WaTL4s
[testimonials]: docs/TESTIMONIALS.md
[soluswiki]: https://github.com/Dechrissen/poke-solus-rgb/wiki
[poke-solus-fr]: https://github.com/persuaded9041/poke-solus-fr
[physical]: physical/
[contact]: https://dechrissen.com/contact
[solusdiscord]: https://discord.gg/YTxu5uM7r6
[howtoplay]: docs/PLAY.md

[jojobear13]: https://github.com/jojobear13
[Vortyne]: https://github.com/Vortyne
[unlink2]: https://krickl.dev/
[quadrixis]: https://github.com/Quadrixis
[persuaded9041]: https://github.com/persuaded9041
[jade]: https://systemrift.com/