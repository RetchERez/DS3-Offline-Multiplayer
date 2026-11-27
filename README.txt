DARK SOULS III OFFLINE MULTIPLAYER - v2.4

Dark Souls III's multiplayer, played completely offline. Computer-controlled phantoms stand in for
other players and follow the game's own multiplayer rules, through the whole game and both DLCs.
In your own world: summon signs with allies to call, dark spirits that invade you, covenant
invaders, Blue Sentinels, purple phantoms, orange messages, bloodstains and ghosts.
New in v2.0, in other worlds: put your own sign down and be summoned, invade with the Red Eye Orb,
answer the call of your covenant, defend the church as a Spear, and fight in the Undead Match.

!! NEVER ON THE NORMAL ONLINE GAME !!
  This mod changes game data files. Going online with changed files can get your account
  soft-banned. Play it OFFLINE, or with Seamless Co-op (see below), and in no other way.
    - In DS3: Settings > Network > Launch Setting > Start offline. Or put Steam in Offline Mode
    - Back up your saves first: copy the folder  %APPDATA%\DarkSoulsIII  somewhere safe
    - Do not take a character you played with this mod online afterwards. Keep a separate save
      for it, or restore your backup before you go back online

WHAT YOU NEED
  - Dark Souls III on Steam, version 1.15.2, with both DLCs (Ashes of Ariandel, The Ringed City)
  - Mod Engine 2 (free, from its GitHub releases page: ModEngine-2.1.0.0-win64)
  - Any of the game's thirteen languages (see LANGUAGES)

INSTALL
  1. Unpack Mod Engine 2 anywhere
  2. Copy the SIX folders inside this archive's "mod" folder (event, map, menu, msg, param, script)
     into Mod Engine 2's "mod" folder. (v1.2 had five; "script" is new and is needed)
  3. Optional: copy "config_darksouls3.toml" from this archive's "Mod Engine 2 settings" folder over
     the one in the Mod Engine 2 folder. It is Mod Engine 2's own settings with nothing to edit
  4. Make sure Steam is already running, then start the game with Mod Engine 2's
     "launchmod_darksouls3.bat". (If Steam is not running, Steam restarts the game WITHOUT the mod
     and you get the plain game: no signs, no messages)
  You have it right when summon signs and orange messages appear in the High Wall of Lothric
  while you are embered and offline.

LANGUAGES
  The mod speaks every language the game does: English, French, German, Italian, Spanish (Spain),
  Spanish (Latin America), Portuguese (Brazil), Polish, Russian, Japanese, Korean, and Simplified and
  Traditional Chinese. It follows the language set in the game. Almost every line is the game's own
  text in that language, and the orange messages are built from the game's own phrases in that
  language. The names of the phantoms stay as they are, like the names of real players.

UPDATING FROM v1.x
  Delete the old folders from Mod Engine 2's "mod" folder first, then copy the six new ones.
  Your save carries over.

WITH SEAMLESS CO-OP
  Players report that the two run together. To try it:
  1. Put Seamless Co-op's own "SeamlessCoop" folder (the one with ds3sc.dll inside) into the
     Mod Engine 2 folder, beside "launchmod_darksouls3.bat"
  2. Copy "config_darksouls3.toml" from "Mod Engine 2 settings\With Seamless Co-op" over the one in
     the Mod Engine 2 folder. It is the same settings file with Seamless Co-op added to the list of
     files Mod Engine 2 loads
  3. Start the game with "launchmod_darksouls3.bat", Steam online
  With Seamless Co-op loaded, only the mod's "your own world" side works: signs to summon from,
  invaders, messages, bloodstains and ghosts. Seamless Co-op switches off the game's offline worlds
  (it says so itself: "Pseudo multiplayer events are currently not available online"), and those
  are the worlds the mod sends you to. So your own soapstone signs, the Red Eye Orb, covenant duty
  and the Undead Match need the game started WITHOUT Seamless Co-op. Take off Blue Sentinels, Blade
  of the Darkmoon, Watchdogs of Farron, Aldrich Faithful and Spears of the Church while Seamless
  Co-op is loaded, or the mod keeps trying to send you to a world that never opens.
  Keeping you off the game's official servers in this setup is Seamless Co-op's job, not this mod's.

UNINSTALL
  Delete those six folders from Mod Engine 2's "mod" folder. Nothing in the game's own folder
  is changed.

WORKS WITH / CLASHES WITH
  It replaces the event scripts and map files of the 16 multiplayer areas and the four arenas, the
  game parameters, two text files, the menu icon file, one AI script file and the Firelink Shrine
  talk script. Any mod that changes the same files (overhauls, randomisers, other parameter mods,
  menu and icon mods, AI mods) will clash with it. Other cosmetic mods (textures, models, sound)
  are fine.

REPORTING A PROBLEM
  Please say the area, what you used or wore, the last line on screen, and the name over the
  phantom's head.

NEW IN v2.0: YOU IN OTHER WORLDS
  Every line on screen is the game's own. A session's world is the same area as its host has it:
  the enemies behind him are already dead, the ones ahead are alive.
  - White Sign Soapstone: your sign lies where you stood (other summon signs go while it is down);
    20 to 50 seconds later you are summoned as a white phantom to a host on his way to the area's
    boss. He may have a second phantom; a dark spirit invades him; a blue spirit may answer. Go
    through the boss's fog after the host and beat the boss with him. Reward: an Ember (a Sunlight
    Medal for a Warrior of Sunlight), and your Ember is restored
  - Using the same soapstone again takes your sign back. One sign at a time. An invasion of your
    own world removes it ("Your summon sign disappeared")
  - Co-op bosses: Vordt, Curse-rotted Greatwood, Crystal Sage, Abyss Watchers, Deacons of the Deep,
    Old Demon King, Pontiff Sulyvahn, Aldrich, Yhorm, Dragonslayer Armour, Twin Princes, Nameless
    King, Soul of Cinder, Sister Friede, Champion's Gravetender, Demon Prince, Halflight, Darkeater
    Midir, Slave Knight Gael. Your own world's boss is left exactly as he was, beaten or not
  - Red Sign Soapstone: you are summoned to a host's side as a dark spirit for a duel
  - Red Eye Orb and Cracked Red Eye Orb: "Searching for another world to invade...", then you
    arrive at one of the game's invasion points and have to find the host. He may have one or two
    phantoms, a blue spirit may come to his aid, a second dark spirit may join you, he may use a
    Seed of a Giant Tree, and a host who is alone and hurt may run for the boss's fog. Reward: a
    Pale Tongue; a Forked Pale Tongue too if the blue spirit dies
  - Mound-makers: the same three items make you a mad phantom. Kill the host, or every phantom he
    had when you arrived. Reward: a Vertebra Shackle
  - Blue Sentinels and Blade of the Darkmoon: wear the covenant and play; after one and a half to
    five minutes you are summoned, without a sign, to a Way of Blue host who is being invaded. Kill
    the dark spirit. Reward: a Proof of a Concord Kept; in Irithyll and Anor Londo a Blade of the
    Darkmoon sometimes earns a Proof of a Concord Well Kept
  - Watchdogs of Farron (Road of Sacrifices, Farron Keep) and Aldrich Faithful (Irithyll, Anor
    Londo): worn in their own territory, you are summoned against a trespasser. Rewards: Wolf's
    Blood Swordgrass, Human Dregs
  - Spears of the Church: worn in the Ringed City once you have beaten Halflight yourself, you are
    summoned to defend the church against a host and his phantoms, with the painting guardians at
    your side. Reward: Filianore's Spear Ornament, two if the host had two phantoms
  - Winning any session restores your Ember, as online. Dying, the host's death, or the Black
    Separation Crystal sends you home

UNDEAD MATCH
  At the Firelink Shrine bonfire, once Champion's Bones have been burned there (the game's own
  rule). Duel, 2 / 4 / 6 Player Brawl, 2 Versus 2 and 3 Versus 3, in the Grand Roof, Dragon Ruins,
  Kiln of Flame and Round Plaza, against fighters from the mod's cast. Three minutes; respawns in
  brawls and team matches, none in a duel; no Estus in a duel, one Estus per life elsewhere.
  You cannot lose souls there: at the edge of death you "have fallen" and are put back.

SMARTER PHANTOMS
  - Dark spirits now fight like players: they dodge, guard, parry, circle, punish a drink or a
    missed swing, heal, and differ from each other (aggressive, patient, circler, roller, turtle,
    parry-fisher). Some bow before the fight
  - Summoned allies greet you once, keep near you, drink Estus, cast their buffs at the boss's
    fog, heal you if they carry a healing miracle, and may thank you after a hard fight
  - Summoned allies in the first seven areas hit harder: about as hard as you, not harder

GHOSTS AND BLOODSTAINS
  - Now and then the white ghost of another player appears near you for a few seconds; near a
    bonfire he sits by it
  - Standing on a bloodstain shows "Touch Bloodstain": a red ghost plays out its death. One replay,
    then rest at a bonfire for the next

RED AND PURPLE SIGNS
  Red duel signs and purple signs show even when you are not embered, and red duel signs stay
  after the area's boss is dead, as online. White and gold signs need the Ember and a living boss.

THE RULES IT FOLLOWS (Dark Souls III's own)
  - Summoning white and gold allies, and being invaded, need you EMBERED and that part of the
    level's boss alive (red and purple signs: see RED AND PURPLE SIGNS)
  - Summon signs are there when you get there: embered, within sight of a spot, a few seconds.
    About half the spots have a sign at any moment; boss doors and bonfires most often
  - Invasions are not instant, and never on a clock: the first comes 1 to 7 minutes after you
    ember (sooner in busy areas, later in quiet ones). After an invasion the game's own cooldown
    runs - 15 minutes alone, 10 with one ally, 5 with two - and then the next invader takes
    another 1 to 7 minutes to find you. Dying or resting does not start these waits over.
    Now and then nobody comes
  - "Summoning phantom..." takes 3 to 7 seconds; the phantom then rises where his sign was
  - Chaos version: the SAME RULES, a far more active community. A sign at every spot within about
    a second, an invader within 8 seconds, half the normal cooldown after each invasion, blues
    always answer, and the covenant zones nearly always send two. Everything else is as in the
    normal game: two allies (three with the Dried Finger), a second invader only with the Dried
    Finger outside the covenant zones, blues only with Way of Blue, no invasions in boss fights,
    no resting with phantoms about
  - Who you meet depends on your level, by Dark Souls III's own rules:
      summon signs (white, gold, purple, red)   the phantom is within 10 + 10% of your level
      dark spirits                              you are from 10% below their level to 20 + 10% above
      purple (Mound-maker) invaders             you are from 10% below their level to 20 + 15% above
      Watchdogs of Farron, Aldrich Faithful     you are from 20 + 20% below their level to 10% above
                                                (they are usually stronger than you, as online)
    Each area's people are levelled for when players really play it:
      High Wall 1-30 (most around 10)           Lothric Castle, Untended Graves 50-110 (65)
      Undead Settlement 8-40 (18)               Grand Archives 60-125 (75)
      Road of Sacrifices, Farron 15-50 (27)     Archdragon Peak 65-135 (84)
      Cathedral of the Deep 18-55 (30)          Kiln 70-180 (88), Painted World 60-180 (85)
      Catacombs, Smouldering Lake 25-70 (40)    Dreg Heap 75-200 (95)
      Irithyll, Anor Londo 35-85 (50)           Ringed City 80-220 (100)
      Irithyll Dungeon, Profaned 40-90 (53)     Filianore's Rest 85-220 (105)
    The level someone is matched at follows how strong he really is: the weaker fighters of an area
    are the ones a low-level player meets, the stronger ones wait for higher levels.
    Everyone is toned down to the level players usually have in each area - most of all at the
    High Wall, where you are level 1-30. That goes for invaders and for the allies you summon:
    a summoned phantom hits about as hard as you do, as online, and does not carry you.
    At any level inside an area's range somebody can be summoned and somebody can invade. Arrive
    early and a few low-level invaders still reach you (level-1 invaders at High Wall, as online).
    Far over-levelled for an area, you find it empty, as online.
    Chaos keeps these level rules but the community is wider: every range reaches a quarter and
    20 levels further each way, so more of an area's people are on offer at your level.
    Not copied: weapon-upgrade matching (a mod cannot read your best weapon), and Blue Sentinels
    and Darkmoons come at any level
  - Orange messages are all over every area: at bonfires, boss doors, illusory walls, and where the
    game puts enemies and invaders. About one in six lies and one in ten is nonsense
  - One invader at a time. A second invader only while the Dried Finger is active.
    (Farron's Watchdogs and the Aldrich Faithful may send two, as in their zones online)
  - A preview, as online: when you use a sign the box shows the phantom's name above "Summon this
    phantom?", and he stands at his sign while you decide, so you can see what he wears and
    carries. (He is a solid white phantom, not see-through, and there is no face portrait:
    those are drawn by the game's online code)
  - Two allies at a time, three with the Dried Finger. Touch another sign and you get
    "Unable to summon phantom"
  - While an invader OR a summoned ally is in your world you cannot rest, as online: the bonfire's
    flame stays but the "Rest at bonfire" prompt is gone until the invader is dead or gone and your
    allies have left (the Offline Separation Crystal sends them home). A bonfire you are standing
    right at when it happens stays usable until you step away from it.
    Walking 150 m away from an ally, or using a Homeward Bone or the Darksign, also sends
    everyone home
  - While an invader is in your world the area's exits are sealed with grey fog, as online. These
    are the game's own 24 multiplayer fog walls, in the game's own places (High Wall, Lothric
    Castle, Undead Settlement, Archdragon Peak, Farron, Grand Archives, Cathedral, Irithyll and
    Anor Londo, Catacombs, Irithyll Dungeon, Painted World), switched on the way the game does it.
    They lift when the invader is dead or gone, and after 5 minutes at the latest (1 minute with the
    Chaos version)
  - Nothing invades during a boss fight. Anyone hostile who is there when you cross the fog goes
    home: dark spirits, covenant invaders, the game's named invaders, and also a red-sign duelist
    or a hostile purple phantom you summoned yourself
  - White and gold allies follow you through the boss fog and leave when the boss dies.
    A gold ally who is still with you at the kill leaves you a Sunlight Medal
  - Blue Sentinels and Blades of the Darkmoon come only if Way of Blue is equipped, one per
    invader, never for Watchdogs or Aldrich Faithful, and not for a purple spirit who is on your side
  - Each stretch of ground closes exactly when the real game closes it for multiplayer: no signs
    (red duel signs included) and no invaders after that. Road of Sacrifices and the Painted World
    stay open until both of their bosses are dead. High Wall closes when Vordt dies, opens again
    once the Dancer can be fought, and closes for good when she dies; the Ringed City works the
    same way around its two bosses.
    Consumed King's Garden closes with Oceiros, Smouldering Lake with the Old Demon King
  - Nothing happens in the Cemetery of Ash or Firelink Shrine, as online
  - Seed of a Giant Tree: for 45 seconds the area's enemies and the invader fight each other
  - Dried Finger (Shrine Handmaid): no cooldown between invasions - the next invader comes as soon
    as one finds you
  - When an invader dies, or one of your allies dies, you get some health back (a stand-in for the
    Estus charge the real game gives back when any phantom dies; a mod cannot add Estus charges)
  - Bosses are tougher when allies are with you: about x1.3 health with one, x1.8 with two, x2 with three
  - If an ally dies while an invader is in your world, you cannot summon again for 3 minutes
    (the game's own cooldown value)
  - With allies you are invaded sooner: the cooldown after an invasion is 15 minutes alone, 10 with
    one ally and 5 with two (the game's own cooldown table)
  - In Farron's woods and after Pontiff, one ally fewer while a Watchdog or Aldrich Faithful is present
  - A covenant does not invade its own: wear Watchdogs of Farron in Farron, or Aldrich Faithful after
    Pontiff, and that covenant leaves you alone. Ordinary dark spirits still come

  - The game's own named invaders are back. Heysel, Kirk, Creighton, the Londor Pale Shades, Tsorig,
    Alva, Kriemhild, Ledo and the Moaning Knight never come when Steam is offline. Here they invade
    where and when the game itself would send them, and beating them counts as it does online
  - An invader arrives at one of the game's own invasion points near you and on your floor, so he
    can actually reach you (seen in play: one arrived 37 m below, was announced and never came)
  - Invaders hunt you. Every hostile phantom has the senses of the game's own invaders: they know
    where you are and come for you, and they do not give up and walk back
  - Anyone left more than 150 m behind goes home, so nobody holds a slot for ever
  - Offline Separation Crystal: using it sends your summoned allies home, and only them. You are
    given one in any multiplayer area. It is not used up. (The Black Separation Crystal cannot be
    used offline: the game itself blocks it unless one of its own phantoms is with you)
  - The game's own NPC summons (Sirris, Anri, Sword Master...) count toward the two-ally limit

MESSAGES ON THE GROUND
  1,378 orange messages across the game, written the way players write them with the game's own
  phrases: by bonfires, before boss doors, and in odd places. Like online, some help and some lie.
  They are at the spots where the game puts enemies and invaders, and out on open ground where
  things walk. They come and go as online, more slowly than bloodstains: about six in ten are
  there at any moment, a message stays for 4 to 15 minutes and a bare spot gets a new one 2 to
  10 minutes later. Notes at bonfires, boss doors and real illusory walls are there most often.
  - Most real illusory walls have an honest note ("Illusory wall ahead", "Try attacking").
    A few have a misleading one ("Liar ahead", "Dead end ahead"), and some have no note at all.
    The note is on both sides of the wall, so you will find a second one inside the hidden room
  - Elsewhere, 89 notes claim an illusory wall where there is only a wall
  - Mimics: most have a warning in front ("Mimic ahead", "Try attacking"), a few have "Treasure ahead",
    some have nothing. And some ordinary chests are called a mimic
  - Beside drops: mostly a warning ("Be wary of hole", "Danger zone ahead"), sometimes "Try jumping"
  They cannot be rated.

BLOODSTAINS
  1,190 bloodstain spots across the game, on open ground: where things walk, not where they stand.
  Most are where a level kills people: outside boss doors, beside the ambush where several come
  at once, beside the tough enemy, where invaders catch their host, beside drops. There are two or
  three in front of every mimic. About a quarter are just somewhere, the way people really die.
  They come and go while you play, as online. About a quarter are there when you arrive. A stain
  lies for one to four minutes and fades; a bare spot gets a new one some minutes later. So the
  same corridor looks different each time you pass.
  They are the same with the Chaos version.
  They are only the mark on the ground - touching one does nothing, there are no deaths to replay
  offline.

PURPLE (MAD) PHANTOMS
  Each one is either on your side or against you from the moment it arrives, and stays that way.
  About five in six are against you and one in six helps.
  You cannot tell which until it acts. Purple allies do not enter boss fog.
  Enemies leave hostile purple phantoms and red-sign duelists alone, as they do invaders.

WHO YOU MEET
  The game itself only creates a few dozen of these people in one area, and any more than that
  simply do not exist: their signs would summon nobody. So each area holds at most 32,
  fewer where the game keeps many characters of its own, and every sign you see can be answered.
  384 people (about one in twenty a troll with no armour, just a weapon, and about one in twenty with a joke name), each with their own name, face, armour, weapons and spells - no two carry the same kit
  They are meant to look and fight like players:
  - Geared for where you meet them. Armour is only what a player could have found by that area
    (starting-class sets and Lothric Knight armour at the High Wall, Ringed Knight armour only in
    the Ringed City). The exception everybody has met, the twink with gear from anywhere, is about
    one in ten in the first three areas (where twinks really hunt) and one in twenty-five after
  - Every weight. About a quarter travel light and roll fast, most are in between, about a fifth
    wear as much as they can and still roll normally, and about one in ten is over the limit and
    fat-rolls - by what each can really carry, weapons included
  - Infused weapons. About a fifth early and nearly half late carry an infused weapon that suits
    their build and the point in the game: Raw and Fire early, Heavy or Sharp by build, Crystal for
    sorcerers, Lightning for the faithful, Chaos and Dark later. Nobody who buffs his weapon has an
    elemental infusion, since the game would not let him buff it
  - Resistance gear. The stoneplate rings (flame, thunder, magic, dark) and the poison, bleed, curse
    and frost rings are worn too, as people wear them for a boss or a swamp
  - Weapons as upgraded as players' are by then: +0 to +2 at the High Wall, +2 to +4 around Farron,
    +5 to +7 in Irithyll, +7 to +9 in Lothric Castle, +9 or +10 at the end
  - Dressed like players. Armour comes from the game's whole catalogue (80 full sets). Most wear a
    matching set, many go helmetless or swap the helmet, some mix two sets, a few wear something odd.
    Heavy fighters stay in heavy armour and casters in cloth
  - Armed like players. Each is built on one of the game's own fighter builds.
    Weapons are swapped only for others with the same moveset and weapon skill that they can wield,
    at the same upgrade (a Flamberge user may carry a Bastard Sword), so they still fight properly
  - Casting like players. A spell is only swapped for one of the same school and the same kind -
    thrown for thrown, heal for heal - that the character could know. Buffs are never swapped
  - Built like players. Each has their own stat spread - balanced, tank (more health), stamina, or
    glass cannon (hits harder, dies faster) - the rings a player of that level and kit would wear,
    and their own number of Estus. Two people with the same weapons do not fight the same fight
  - Fighting like 70 different people. Besides the invaders and phantoms the game already has, the
    fighting scripts of Siegward, Patches, Leonhard, Hawkwood, the Butcher and a Painting Guardian
    are now in the hostile cast
  - Named to match. "Bonk Stick" carries a club, "Parry King" a parrying shield, "Fat Roll Fred"
    the heaviest armour; a "Ser" or "Knight" wears plate
  - Matched to the area. Early areas get low-level builds, late areas high-level ones, and the same
    build only comes round again in an area once the others have appeared
  Summoned allies get straight to it. About one in seven stands where he was summoned until you
  lead on (walk 7 m away, or wait 40 seconds), and about one in four runs ahead on his own.
  Nobody gestures on arrival: in play a phantom kept gesturing instead of fighting, so the
  greetings are gone.
  Some invaders gloat if they kill you. They are stronger if you
  are over-levelled for the area; about 1 in 5 invaders is tougher than usual and hits harder, and
  about 1 in 20 hits harder still. An invader's ordinary hit takes about a fifth of your health.

REWARDS  (the first three are NOT what the real game gives the host - see below)
  Dark spirit: Pale Tongue half the time.  Watchdog: Wolf's Blood Swordgrass half the time.
  Aldrich Faithful: Human Dregs half the time.  A gold-sign ally still with you when the boss falls: Sunlight Medal.
  Hostile mad phantom: Vertebra Shackle.  Winning a red-sign duel: Pale Tongue.
  Souls follow the fighter's own level, as online: about 1,000-3,500 at High Wall, far more late on.

WHERE THIS DIFFERS FROM REAL ONLINE, ON PURPOSE OR BY LIMIT
  - Covenant items for beating invaders: online those go to the invader, not to you. Kept so the
    covenants can be ranked up offline at all
  - Purple phantoms: online they can hurt everyone. Here each is fixed as friend or foe
  - Health back instead of an Estus charge when an invader or an ally dies. Ordinary enemies are not tougher while you
    have allies (bosses are). Homeward Bone and the Darksign still work while invaded
  - Strength follows your level, not your weapon upgrade
  - Timers restart when you rest or die

BOTH DLCs ARE COVERED
  Painted World of Ariandel, The Dreg Heap, The Ringed City and Filianore's Rest have their own
  invaders, signs and messages, and their bosses are tougher with allies. The Ringed City's three
  named invaders are restored.

ALLIES AND THE BOSS FOG, EVERYWHERE
  Where the game has a summon of its own before a boss, your white and gold allies walk through
  the fog the way that summon does. Everywhere else (Undead Settlement, Irithyll Dungeon,
  Archdragon Peak, the Painted World, Filianore's Rest, or any ally summoned far from the door)
  a living ally is brought to your side a few seconds after the fight starts.

WHERE v2.0's OTHER WORLDS DIFFER FROM REAL ONLINE
  - Starting a session moves you out of sight for a second or two; the screen may jump
  - Watchdogs, Aldrich Faithful and Spears are called only while you are in their own territory
  - Not co-op goals: the Dancer, the Ancient Wyvern, High Lord Wolnir, Oceiros, Iudex and Champion
    Gundyr
  - Hosts are of their area's level; there is no matching by weapon upgrade
  - Undead Match: always three minutes, fighters keep their phantom colours, no ranks or badges,
    and in a 6 Player Brawl two pairs share a side
  - A bloodstain shows the death only, not the moments before it, and one replay at a time: rest
    at a bonfire for the next
  - No ratings on messages, no passwords, voice chat or trading: those need real players

CHANGELOG
  v2.4
  - Dark spirits no longer drop the weapons and armour of the game's own invaders; you get only the mod's own rewards
  - While you are in another world, your own world's items, summon signs and bonfires are gone; they come back when you are home
  - With Seamless Co-op loaded, the mod's other worlds (your own signs, the orbs, covenant duty) cannot work: Seamless Co-op turns off the game's offline worlds; the read-me now says so
  - If the host dies and you are not sent home within a few seconds, you are sent home
  v2.3
  - Invading: the host could not be locked on to or hurt; the host you invade, and the phantoms and blue spirit at his side, can be fought again
  v2.2
  - Summon signs for stronger players: a character above an area's usual level found invaders there but no white or gold signs at all. The area's strongest white and gold phantoms (at least three, a third of them in a big area) now answer any player above them, as invaders already did
  - Bloodstains: after a replay, resting at a bonfire makes them touchable again; before, only leaving the area or reloading did. One replay at a time, then rest
  - New troubleshooting answers in this read-me: no white signs, and Way of Blue bringing no blue spirit
  v2.1
  - All thirteen of the game's languages: summon prompts, arrival and departure lines, session lines, the Undead Match menu, orange messages and the Offline Separation Crystal show in the language your game is set to
  - Orange messages use only phrases Dark Souls III's own message menu can make; some used words from the earlier games
  v2.0
  - You as the phantom: White Sign Soapstone (co-op to the boss in every area), Red Sign Soapstone, Red Eye Orb and Cracked Red Eye Orb, in all sixteen areas
  - Covenant duty: Blue Sentinels, Blade of the Darkmoon, Watchdogs of Farron, Aldrich Faithful, Spears of the Church, Mound-makers, Warrior of Sunlight; every covenant reward can be earned
  - Undead Match at the Firelink Shrine bonfire: six formats, four arenas
  - New invader AI: dodging, guarding, parrying, circling, punishing, healing, six fighting styles
  - Livelier summoned allies: a greeting, following, Estus, buffs at the boss's fog, healing
  - Ghosts of other players, also seated at bonfires; bloodstains can be touched
  - Summoned allies hit harder in the first seven areas
  - Red duel signs and purple signs no longer need the Ember; red duel signs stay after the boss is dead
  - A blue spirit no longer answers a red-sign duel or a covenant-territory invader
  - Install is now SIX folders ("script" is new), and a ready-made Mod Engine 2 settings file is included
  v1.2a
  - Warriors of Sunlight no longer invade: they are met at gold summon signs only. The invaders who were Sunlight ones are ordinary dark spirits
  v1.2
  - New item, the Offline Separation Crystal: sends your summoned allies home. You are given one in any multiplayer area. The Black Separation Crystal cannot be used offline, as the game itself blocks it
  - Fixed invasions that never came: an invader arrives at one of the game's own invasion points near you, on your floor, and no longer only at his own spot
  - Dying or resting no longer starts the wait for an invader over
  - The cooldown after an invasion is the game's own: 15 minutes alone, 10 with one ally, 5 with two, none with the Dried Finger, and then however long the next invader takes to find you. It lasts through death and rest
  - Chaos has half that cooldown; it had almost none
  - Invaders hit much harder. Their attack was cut far too low, most of all in the High Wall of Lothric; an ordinary hit now takes about a fifth of your health in the early areas
  - Tougher invaders now also hit harder, where before they only had more health
  - A player above an area's level range is still invaded, by the strongest dark spirits there
  - The mod now includes the game's menu icon file, for the new crystal's icon: copy five folders, not four
  v1.1
  - Fixed summon signs that summoned nobody: the game only creates so many phantoms per area, so each area now holds no more than it can (384 in all, up to 32 per area)
  - Invaders now arrive only when you are near their arrival point and on its floor, so an invader who is announced can always reach you
  - Invasion timing retuned: the first comes 1 to 7 minutes after you ember, later ones 5 to 15 minutes apart
  - Phantoms no longer gesture on arrival and get straight to it
  - Purple phantoms are now hostile five times in six and helpful one time in six
  - Phantoms no longer cast the same buff over and over: everyone keeps the buff their fighting style expects
  - Invaders and duelists carry half the Estus, as online
  - Joke names are now about one phantom in twenty
  v1.0
  - Summon signs in every area: white, gold, red duel signs and purple, with a preview of the phantom
  - Dark spirits, Sunlight and Mound-maker invaders, and Watchdogs of Farron and Aldrich Faithful in their zones
  - Blue Sentinels and Blades of the Darkmoon answer when Way of Blue is equipped
  - The game's own named invaders (Heysel, Kirk, Creighton and the rest) restored offline
  - 384 phantoms with their own names, faces, gear, builds and ways of turning up
  - Dark Souls III's level ranges decide who you meet, and everyone is toned to the area's level
  - 1,378 orange messages that come and go, some honest and some not
  - 1,190 bloodstain spots that come and go while you play
  - Bonfires lock and area exits fog over while phantoms are in your world
  - Boss rules as online: no invasions in a boss fight, allies cross the fog, bosses are tougher with allies
  - Ember, Dried Finger, Seed of a Giant Tree, Way of Blue and the Black Separation Crystal all do their job
  - The whole base game and both DLCs
  - Chaos version: the same rules in a far busier world

IF SOMETHING LOOKS WRONG
  - Nothing happens at all: you must be embered, and the area's boss must be alive. Invasions take
    minutes to start, as online; the Dried Finger brings them sooner
  - No white or gold signs: they need the Ember (use one, or beat a boss), the area's boss alive,
    and you within sight of a sign spot (bonfires and boss doors most often). About half the spots
    have a sign at a time, so walk on or wait a little. Red and purple signs need no Ember
  - Way of Blue brings no blue spirit: blues answer an uninvited dark spirit only, not a Watchdog,
    an Aldrich Faithful, a red-sign duel or one of the game's own named invaders. Even then not
    every invasion gets an answer: between one in five and one in three get none, by area
  - Nobody summons you after you put your sign down: wait up to a minute; if your own world is
    invaded the sign goes and you must write it again
  - "Undead Match" is not in the bonfire's list: burn Champion's Bones at the Firelink Shrine
    bonfire first
  - Phantoms stand still and never fight: the "script" folder is missing from Mod Engine 2's "mod"
    folder
  - An ally arrives and just stands there: about one in five waits for you to lead. Walk 7 m away
    and he follows; he also starts if he is hit, or after 40 seconds
  - Your allies will not leave: use the Offline Separation Crystal (you are given one in any
    multiplayer area). The Black Separation Crystal sends YOU home from another world
  - With the Chaos version an invader comes within seconds of your embering, so bonfires are locked
    and exits fogged at once. Kill him and the cooldown gives you some minutes
  - When you report a problem, please say the area, and the name over the phantom's head
