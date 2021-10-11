<p align="center">
  <a href="https://github.com/TShock/TShock" title="Click to visit the main project">
    <img src="https://tshock.co/newlogo.png" alt="TShock for Terraria">
  </a>
</p>

This is the TShock plugin repository. All plugins from catbox have been analyzed by manual review processes that may not be perfect. While we believe these files are safe to run, we cannot guarantee a perfect review. All plugins undergo decompilation-based review analysis, but some plugins undergo additional scrutiny.

----

## Verified developers! 👨‍💻💻

Developers in this category are in agreement with (or part of) the Pryaxis team and understand the requirements behind producing a safe plugin. Each of these developers have their own entries, and their plugins are available on the linked repositories, website or collection repository.

* [Rozen4334](https://github.com/Rozen4334)
  * Maintainer/creator of: ChatManager, WorldEdit, Buildmode and many others.
  * [Contact](https://rozen.one)
  * [Plugin collection](https://github.com/Rozen4334/TShock-plugins)

*To become a verified plugin developer, check out the [verification](https://github.com/Pryaxis/Plugins/tree/master/Verification) process.*

## List of all plugins! 🧪☕️⚡️

*To submit a plugin, check out the [submission](https://github.com/Pryaxis/Plugins/tree/master/submission) process.*

#### Contents:
   - [Server side characters](#ssc-server-side-characters)
   - [PvP/PvE](#pvppve)
   - [Building](#building)
   - [Moderation](#moderation)
   - [Management](#management)
   - [Worlds](#worlds)
   - [Custom server logic](#custom-server-logic)
   - [Chat](#chat)
   - [Miscellaneous](#miscellaneous)

#### Tags:
- 🔨 This plugin is maintained by another developer than the one who originally made it.
- 🔗 This plugin is compatible with versions before 4.5.x

### SSC (Server side characters)
* Vanillafier
  * Sets up your server to run like the vanilla Terraria server in 1 easy command
  * Built on TShock 4.5.0
  * [Download](https://files.catbox.moe/cy8sca.zip)
  * [Source Code](https://github.com/Pryaxis/Vanillafier)
* [Character Reset (SSC)](https://github.com/bippity/CharacterReset) by [Bippity](https://github.com/bippity), updated by [moisterrific](https://github.com/moisterrific)
  * Allows you to reset SSC player data without the hassle of database editing. 
  * Built and tested on TShock 4.5.2.0 (April Lyrids edition).
  * [Download v1.0.3](https://files.catbox.moe/seefnu.zip)
  * [Documentation](https://github.com/moisterrific/CharacterReset/blob/master/README.md)
  * [Source Code](https://github.com/moisterrific/CharacterReset/blob/master/CharacterReset.cs)
* CustomMediumcore by Miffyli
  * Ease Mediumcore by selecting which items are dropped upon death.
  * Requirements: Server-side characters enabled. Players must have "Casual" difficulty.
  * Place `drop_item_ids.txt` next to `TerrariaServer.exe`.
  * Tested on TShock 4.4.0 Pre-3.
  * [Download v1.4.0.1](https://files.catbox.moe/2tplf7.zip)
  * [Source code and documentation](https://github.com/Miffyli/TerrariaCustomMediumcore)

### PvP/PvE
* [Normal Boss Bags](https://github.com/Quinci135/NormalBossBags) by Quinci
  * Makes normal mode bosses drop treasure bags as if it were expert mode
  * Built and tested on TShock 4.4.0 Pre-12
  * [Download v1.0](https://files.catbox.moe/647789.zip)
  * [Source code](https://github.com/Quinci135/NormalBossBags)

### Building
* [Invincible Tiles (and walls)](https://github.com/Olink/Invincible-Tiles) by Olink
  * Adds the ability for players to blacklist tile ids and wall ids, preventing users from breaking said tiles/walls.
  * Tested on TShock 4.4.0 Pre-6.
  * [Download v1.0](https://files.catbox.moe/35914m.dll)
  * [Source code](https://github.com/Olink/Invincible-Tiles)
* [Creative Mode](https://tshock.co/xf/index.php?resources/creative-mode.19/) by Bippity
  * A simple "Creative Mode" for players
  * Built on TShock 4.4.0 Pre-8
  * [Download](https://files.catbox.moe/tkfyvq.dll)
  * [Documentation/Source Code](https://github.com/bippity/CreativeMode)
* 🔗 [WorldEdit](https://github.com/Brycey92/WorldEdit)
  * Adds mass tile editing commands.
  * Built on TShock 4.4.0 Pre-11.
  * [Download v1.8.0](https://files.catbox.moe/2h14dl.zip)
  * [Source code](https://github.com/Brycey92/WorldEdit)

### Moderation
* ZAdminCmds
  * Zaicon's ZAdminCmds updated to 1.4. (https://github.com/Zaicon/ZAdminCmds)
  * Tested on TShock 4.4.0 Pre-10.
  * [Download](https://files.catbox.moe/gvqzxu.dll)
  * [Source code](https://github.com/Rustly/ZAdminCmds)
* CloneNotify
  * Zaicon's CloneNotify updated to 1.4. (https://github.com/Zaicon/CloneNotify)
  * Tested on TShock 4.4.0 Pre-10.
  * [Download](https://files.catbox.moe/sqq56g.dll)
  * [Source code](https://github.com/Rustly/CloneNotify)
* 🔨 [Ghost](https://github.com/DannyDan77/Ghost) by [DannyDan77](https://github.com/DannyDan77), updated by [moisterrific](https://github.com/moisterrific)
  * Allows admins to become invisible to other players.
  * Built and tested on TShock 4.4.0 Pre-11.
  * [Download v1.2.0](https://files.catbox.moe/rh3myj.zip)
  * [Documentation (pls read!)](https://github.com/moisterrific/Ghost/blob/master/README.md)
  * [Source Code](https://github.com/moisterrific/Ghost/blob/master/GhostPlugin/GhostPlugin.cs)
* 🔗 🔨 [PlayerInfo](https://github.com/Brycey92/PlayerInfo/tree/terraria-1.4) by [ParadonX](https://github.com/ParadonX), updated by [Brycey92](https://github.com/Brycey92)
  * A player info modifier/checker.
  * Built on TShock 4.4.0 Pre-11.
  * [Download v1.8](https://files.catbox.moe/fwqfl5.zip)
  * [Source code](https://github.com/Brycey92/PlayerInfo/tree/terraria-1.4)

### Management
* ShortCommands
  * Zaicon's ShortCommands updated to 1.4. (https://github.com/Zaicon/ShortCommands)
  * Tested on TShock 4.4.0 Pre-10.
  * [Download](https://files.catbox.moe/3wdlk7.dll)
  * [Source code](https://github.com/Rustly/ShortCommands)
* [TServerWeb - Online Server Manager for TShock](https://www.tserverweb.com/) by XGhozt
  * Manage your TShock server from the web, run commands, manage players, groups, permissions and more.
  * Tested on TShock 4.4.0 Pre-7.
  * Addon: [TServerWeb In-Game Vote Plugin](https://gitlab.xghozt.com:2345/tsw/TSWVote/raw/master/Build/TSWVote.dll) / [Source Code](https://gitlab.xghozt.com:2345/tsw/TSWVote)
  * Addon: [TServerWeb Remote Console](https://gitlab.xghozt.com:2345/tsw/tswconsole/raw/master/Build/TSWConsole.dll) / [Source Code](https://gitlab.xghozt.com:2345/tsw/tswconsole)
  * [Discord Server](https://discord.gg/s63fqsW)
* [ListPluginsPlugin](https://github.com/Arthri/ListPluginsPlugin) by Arthri
  * Provides commands for listing the currently loaded plugins.
  * Tested on TShock 4.5.5
  * [Download v1.0.1](https://files.catbox.moe/yqgpwt.dll)
  * [Documentation](https://github.com/Arthri/ListPluginsPlugin#listpluginsplugin)
  * [Source code](https://github.com/Arthri/ListPluginsPlugin)
* [TDiffBackup](https://github.com/tieonlinux/TDiffBackup) by [tieonlinux](https://github.com/tieonlinux)
  * World file backup system
  * Built on TShock 4.4.0 Pre-11
  * [Download](https://files.catbox.moe/f8axjx.zip)
  * [Documentation/Source Code](https://github.com/tieonlinux/TDiffBackup)
* [Smart Regions](https://github.com/ZakFahey/SmartRegions) by GameRoom
  * Run programmable commands when a player is in a region.
  * Compatible with TShock 4.5.x
  * [Download v1.3.1](https://files.catbox.moe/pusl50.dll)
  * [Documentation](https://github.com/ZakFahey/SmartRegions/blob/master/README.md)
  * [Source code](https://github.com/ZakFahey/SmartRegions)
* 🔨 [SummonLimit](https://github.com/moisterrific/SummonLimit) by [Newy](https://github.com/newyrose), updated by [moisterrific](https://github.com/moisterrific)
  * Prevents summon hacking.
  * Built on TShock 4.4.0 Pre-11.
  * [Download](https://files.catbox.moe/mr52x7.zip)
  * [Source code](https://github.com/moisterrific/SummonLimit)
* 🔨 [TshockLogs_Explosives](https://github.com/moisterrific/TshockLogs_Explosives) by [slzn](https://github.com/slzn), updated by [moisterrific](https://github.com/moisterrific)
  * Helps to track explosives(Bomb, Dynamite, etc... ) usage.
  * Built on TShock 4.4.0 Pre-11.
  * [Download](https://files.catbox.moe/flnmuh.zip)
  * [Documentation](https://github.com/moisterrific/TshockLogs_Explosives#config)
  * [Source code](https://github.com/slzn/TshockLogs_Explosives)
* 🔗 [TShockPrometheus](https://github.com/swantzter/tshock-prometheus) by [Swantzter](https://github.com/swantzter)
  * Exposes the current player count on the server to prometheus
  * Tested on TShock 4.4.0 Pre-15.
  * [Download v1.0.0](https://files.catbox.moe/lfi2sm.zip)
  * [Source code](https://github.com/swantzter/tshock-prometheus)
* 🔗 [TShock Server REST Mobile](https://github.com/KohlsAdrian/tshock_server_rest) by [647](https://github.com/KohlsAdrian)
  * Manage players/users, bans, world, groups and server directly from your mobile device.
  * Tested on TShock 4.4.0 Pre-15.
  * [Android APKs](https://github.com/KohlsAdrian/tshock_server_rest_client/tags) (iOS Should build directly from MacOS using Flutter SDK and XCode installed)
  * [Source code Flutter App](https://github.com/KohlsAdrian/tshock_server_rest_client)
  * [Source code Dart Wrapper (Doc)](https://github.com/KohlsAdrian/tshock_server_rest)
* [AutoRegister](https://github.com/moisterrific/TShockAutoRegister) by [brian91292](https://github.com/brian91292), updated by [moisterrific](https://github.com/moisterrific)
  * Temporarily removed due to a secure code review failure. A defect in the design by @brian91292 would lead to generating predictable passwords that could be easily obtained by malicious servers.
  * [Source code](https://github.com/moisterrific/TShockAutoRegister)

### Worlds
* [MultiSCore](https://github.com/Megghy/MultiSCore/releases/) by Megghy
  * An easy-to-use Terraria multi-world plugin that allows you to teleport directly to other servers in-game and back via a proxy
  * You can adjust the plugin language in the configuration file or modify it to your preferred sentence
  * Tested on TShock 4.5.5
  * [Download v1.5.2](https://files.catbox.moe/h1plqy.dll)
  * [Documentation](https://www.bbstr.net/r/75/)
  * [Source code](https://github.com/Megghy/MultiSCore/)
* [AdditionalPylons](https://github.com/Adventure-Terraria-Server-Project/AdditionalPylons-Plugin) by [Stealownz](https://github.com/Stealownz)
  * Allows placing additional (infinite) pylons more than default Terraria limits
  * Tested on TShock 4.5.4
  * [Download v1.1.0.0](https://files.catbox.moe/hx1lqm.dll)
  * [Source code](https://github.com/Adventure-Terraria-Server-Project/AdditionalPylons)
* [WorldMapper](https://github.com/drunderscore/WorldMapper) by Dr. Underscore
  * Allows generation of a PNG map of the entire world.
  * Tested on TShock 4.5.2
  * [Download](https://files.catbox.moe/7qfpmf.zip)
  * [Source code](https://github.com/drunderscore/WorldMapper)
* AdvancedWarpplates
  * Rofle's AdvancedWarpplates but actually including a build in the repo. (https://github.com/popstarfreas/AdvancedWarpplates)
  * Tested on TShock 4.4.0 Pre-10.
  * [Download](https://files.catbox.moe/5evaiv.dll)
  * [Source code](https://github.com/Rustly/AdvancedWarpplates)
* 🔨 [NPC Blocker](https://github.com/moisterrific/NPCBlocker2) by [Olink](https://github.com/Olink), updated by [moisterrific](https://github.com/moisterrific)
  * Allows you to block certain NPCs from spawning in the world.
  * Built and tested on TShock 4.5.3.0
  * [Download v2.0.0](https://files.catbox.moe/tfy6tb.zip)
  * [Documentation](https://github.com/moisterrific/NPCBlocker2/blob/main/README.md)
  * [Source Code](https://github.com/moisterrific/NPCBlocker2/blob/main/NPCBlocker/NPCBlocker.cs)
* 🔨 [InfiniteChestsV3](https://github.com/Zaicon/InfiniteChestsV3) by [Zaicon](https://github.com/Zaicon), updated by [moisterrific](https://github.com/moisterrific)
  * Allows "infinite" chests and additional features such as auto-refill, password-protected chests, and more.
  * Built and tested on TShock 4.5.2.0 (April Lyrids edition).
  * [Download v1.2.1](https://files.catbox.moe/5zjurx.zip)
  * [Documentation](https://github.com/moisterrific/InfiniteChestsV3/blob/master/README.md)
  * [Source Code](https://github.com/moisterrific/InfiniteChestsV3/tree/master/InfiniteChestsV3)
* 🔨 🔗 [RodHealer](https://github.com/ancientgods/RodHealer) by [ancientgods](https://github.com/ancientgods), updated by [moisterrific](https://github.com/moisterrific)
  * Prevents players from losing HP when spamming the Rod of Discord.
  * Built and tested on TShock 4.4.0 Pre-11.
  * [Download v1.2.0](https://files.catbox.moe/gocgdm.zip)
  * [Documentation](https://github.com/moisterrific/RodHealer/blob/master/README.md)
  * [Source Code](https://github.com/moisterrific/RodHealer/blob/master/Rodhealer/main.cs)
* 🔨 🔗 [World Refill](https://github.com/k0rd/WorldRefill) by [K0rd](https://github.com/k0rd), updated by [Illuminousity](https://github.com/Illuminousity)
  * Refill your world with structures and resources!
  * Built and tested on Tshock 4.4.0 Pre-11.
  * [Download v2.1.3](https://files.catbox.moe/3fdrrv.zip)
  * [Documentation](https://github.com/Illuminousity/WorldRefill/blob/master/README.md)
  * [Source Code](https://github.com/Illuminousity/WorldRefill)

### Custom server logic
* Tiled by thanatos-tshock
  * Provides alternate tile implementations which improve performance and memory usage
  * Tested on TShock 4.4.0 Pre-3.
  * [Download v1.4.0.0](https://files.catbox.moe/qmcthi.dll)
  * [Source code](https://github.com/thanatos-tshock/Tiled)
* JourneyMixer
  * Allows journey mode characters to join a non journey mode world and now visa versa.
  * Tested on prerelease 15.
  * Source https://github.com/Rustly/JourneyMixer
  * Download https://files.catbox.moe/d9r1jr.dll
* 🔗 [Crossplay](https://github.com/Moneylover3246/Crossplay) by Moneylover3246
  * Allows crossplay to happen in terraria servers via packet handling and manipulation
  * Tested on TShock 4.5.5.
  * [Download v1.4.2.1 - For TShock 4.5.4+](https://files.catbox.moe/vrszug.dll)
  * [Download v1.1.1 - For TShock 4.4.0 pre-12](https://files.catbox.moe/jaxve6.dll)
  * [Documentation](https://github.com/Moneylover3246/Crossplay/blob/main/README.md)
  * [Source code](https://github.com/Moneylover3246/Crossplay/)

### Chat
* [TerrariaChatRelay](https://github.com/xPanini/TCR-TerrariaChatRelay-TShock) by [Lady Narnia (xPanini)](https://github.com/xPanini)
  * Highly customizable Terraria Chat Relay with multiple Discord server support
  * Tested on TShock 4.5.5.
  * [Download v0.9.2](https://files.catbox.moe/avy37t.zip)
  * [Documentation](https://github.com/xPanini/TCR-TerrariaChatRelay/wiki)
  * [Source code](https://github.com/xPanini/TCR-TerrariaChatRelay-TShock)
* [IRCrarria](https://github.com/lemon-sh/IRCrarria) by lemon-sh
  * A very simple IRC<->Terraria chat bridge.
  * Tested on TShock 4.5.5.
  * [Download v1.0.0](https://files.catbox.moe/9sufi0.zip)
  * [Source code](https://github.com/lemon-sh/IRCrarria)
* [Terracord](https://github.com/FragLand/terracord) by [ldilley](https://github.com/ldilley)
  * A Discord <-> Terraria bridge plugin for TShock
  * Tested on TShock 4.5.5.
  * [Download v1.3.1](https://files.catbox.moe/u9wrwm.zip)
  * [Documentation](https://github.com/FragLand/terracord/blob/master/.github/README.md)
  * [Source code](https://github.com/FragLand/terracord)

### Miscellaneous
* [AutoTeam](https://github.com/TerraTrapezium/AutoTeam) by [Metacinnabar](https://github.com/Metacinnabar)
  * Automatically assigns players a configurable team on world join.
  * Tested on TShock 4.5.5
  * [Download v1.0.0](https://files.catbox.moe/14tcj8.dll) (`AutoTeam.dll`)
  * [Source code](https://github.com/TerraTrapezium/AutoTeam)
* FACommands by MineBartekSA
  * Originally created by Hiarni & Zaicon
  * Fun and Admin Commands
  * Tested on TShock 4.4.0 Pre-12.
  * [Download v1.7.1](https://files.catbox.moe/elsv0g.dll)
  * [Source code](https://github.com/MineBartekSA/FACommands)
* TerraJump by MineBartekSA
  * Simple plugin that adds JumpPads
  * Tested on TShock 4.4.0 Pre-15.
  * [Download v2.3.1](https://files.catbox.moe/oc1a1a.dll)
  * [Source code](https://github.com/MineBartekSA/TerraJump)
* [Team Commands](https://github.com/ZakFahey/Team-Commands) by GameRoom
  * Run commands for a whole team.
  * Built on TShock 4.4.0 Pre-8
  * [Download v1.2](https://files.catbox.moe/8mlw7v.dll)
  * [Documentation](https://github.com/ZakFahey/Team-Commands/blob/master/README.md)
  * [Source code](https://github.com/ZakFahey/Team-Commands)
* [AFK Warp/Kick Plugin](https://tshock.co/xf/index.php?resources/afk-warp-kick.104/) by Bippity
  * Idle players will be warped/kicked after a defined time
  * Built on TShock 4.4.0 Pre-12
  * [Download v1.1](https://files.catbox.moe/bmm85t.zip)
  * [Documentation/Source Code](https://github.com/bippity/AFK)
* [Buff Emoticons](https://github.com/Dylanswaggerino/Buff-Emotions) by The Killer [NL]
  * Gives the user a in-game buff for 46 seconds!
  * Tested on TShock 4.4.0 Pre-15.
  * [Download v2.1](https://files.catbox.moe/ta8nc9.dll)
  * [Documentation](https://github.com/Dylanswaggerino/Buff-Emotions/blob/master/README.md)
  * [Source code](https://github.com/Dylanswaggerino/Buff-Emotions)
* 🔨 [InfiniteChestsV3](https://github.com/Zaicon/InfiniteChestsV3) by [Zaicon](https://github.com/Zaicon), updated by [moisterrific](https://github.com/moisterrific)
  * Allows "infinite" chests and additional features such as auto-refill, password-protected chests, and more.
  * Built and tested on TShock 4.5.2.0 (April Lyrids edition).
  * [Download v1.2.1](https://files.catbox.moe/5zjurx.zip)
  * [Documentation](https://github.com/moisterrific/InfiniteChestsV3/blob/master/README.md)
  * [Source Code](https://github.com/moisterrific/InfiniteChestsV3/tree/master/InfiniteChestsV3)
* 🔗 [Essentials+](https://github.com/QuiCM/EssentialsPlus) by [QuiCM](https://github.com/QuiCM) (and various others <3)
  * Compatible with TShock v4.5.x
  * Numerous 'essential' tools for enhancing gameplay & administration capabilities
  * [Download](https://files.catbox.moe/2z23s9.dll)
  * [Source](https://github.com/QuiCM/EssentialsPlus)
* 🔗 [Calculator](https://github.com/edg-l/Calculator) by [edg-l](https://github.com/edg-l)
  * A calculator plugin.
  * Built on TShock 4.4.0 Pre-11.
  * [Download v1.0.0.0](https://files.catbox.moe/nkieg4.zip)
  * [Source code](https://github.com/edg-l/Calculator)
* 🔗 [Auto Team](https://github.com/dredhorse/tShockAutoTeam) by Don Redhorse
   * Joins the players to a team based on permissions
   * Tested on TShock 4.4.0 Pre-12.
   * [Download v1.0.0](https://files.catbox.moe/1ouznb.dll)
   * [Source code and documentation](https://github.com/dredhorse/tShockAutoTeam)
----

### Changes

These are the changes made to this page that aren't really plugin related.

1. Created system for submitting plugins. - May 18, 2020.
2. Updated system to include TShock test version. - May 18, 2020.
3. Add slow plugin review scheme. - June 18, 2020.
4. Plugin slowness scheme revised to require one plugin per PR to be elligable. - May 28, 2021
5. Clarified review process, added tips for making reviws faster. - Aug 11, 2021
7. Introducing verified developers, creating methods to apply and verify yourself as part of this group. - Oct 3, 2021
8. Categorizing plugins into an assortment of gameplay types. - Oct 3, 2021
9. Moving verification & submission process to different README's. - Oct 6, 2021

### Final note

You can tag your plugins on GitHub with the `tshock` tag, the `tshock-plugin` tag or the `terraria` tag.
