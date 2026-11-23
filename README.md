# DS3 Offline Multiplayer

The full Dark Souls III multiplayer experience, entirely offline.

Computer-controlled phantoms take the place of other players and follow the game's own multiplayer rules, through the whole base game and both DLCs. Every line on screen is the game's own.

**Download:** the [latest release](../../releases/latest), or [Nexus Mods](https://www.nexusmods.com/darksouls3/mods/2442).

> **Never on the normal online game.** This mod changes game data files. Going online with modified files can get your account soft-banned. Play it offline, or with Seamless Co-op, and in no other way.

## New in v2.0: you in other worlds

- **White Sign Soapstone**: put your sign down, be summoned to a host on his way to the area's boss, follow him through the fog and beat the boss together
- **Co-op to 19 bosses**, from Vordt to Slave Knight Gael; your own world's boss is left exactly as he was
- **Red Sign Soapstone**: be summoned to a host's side for a duel
- **Red Eye Orb and Cracked Red Eye Orb**: invade and hunt the host down
- **Mound-makers**: the same three items make you a mad phantom
- **Blue Sentinels and Blade of the Darkmoon**: summoned without a sign to a Way of Blue host who is being invaded
- **Watchdogs of Farron and Aldrich Faithful**: summoned against a trespasser in their own territory
- **Spears of the Church**: defend the church of the Ringed City, with the painting guardians at your side
- **Undead Match** at the Firelink Shrine bonfire: six formats, four arenas
- **Smarter phantoms**: dark spirits dodge, guard, parry, circle and punish in six fighting styles; summoned allies greet you, keep near you, buff at the boss's fog and heal
- **Ghosts and bloodstains**: ghosts of other players, also seated at bonfires; bloodstains can be touched

## In your own world (since v1.0)

- White, gold, red and purple summon signs, with 384 named phantoms behind them
- Dark spirits, Watchdogs of Farron and Aldrich Faithful who invade you; Blue Sentinels who answer Way of Blue
- The game's named invaders restored
- 1,378 orange messages and 1,190 bloodstains
- The game's own rules: level ranges, ally and invader limits, invasion cooldowns, bonfire lock, exit fog, boss fog rules
- Two versions: normal pacing, and **Chaos**, the same world far busier

## Requirements

- Dark Souls III on Steam, version 1.15.2, with both DLCs
- [Mod Engine 2](https://github.com/soulsmods/ModEngine2/releases) (ModEngine-2.1.0.0-win64)
- The game set to English

## Install

1. Unpack Mod Engine 2 anywhere
2. Copy the six folders inside the archive's `mod` folder (`event`, `map`, `menu`, `msg`, `param`, `script`) into Mod Engine 2's `mod` folder
3. Optional: copy `config_darksouls3.toml` from the archive's `Mod Engine 2 settings` folder over the one in the Mod Engine 2 folder
4. Set the game to start offline: Settings > Network > Launch Setting > Start offline
5. With Steam already running, start the game with Mod Engine 2's `launchmod_darksouls3.bat`

Install the normal archive **or** the Chaos archive, not both. The full read-me, with every rule and the changelog, is `README.txt` inside each archive and [here](README.txt).

## With Seamless Co-op

Players report that the two run together. Put Seamless Co-op's `SeamlessCoop` folder into the Mod Engine 2 folder, copy `config_darksouls3.toml` from `Mod Engine 2 settings\With Seamless Co-op` over the one in the Mod Engine 2 folder, and start with `launchmod_darksouls3.bat`. While in a Seamless Co-op session, use only the "your own world" side of the mod.

## Credits

- Inspired by Wayward Tarnished - Offline Invasions for Elden Ring
- Mod Engine 2 by the soulsmods team
- SoulsFormats and DarkScript3
- The Dark Souls modding community

Works great with [DS3 Pause](https://github.com/RetchERez/DS3-Pause).
